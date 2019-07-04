# Das ActivityPub Protokoll

**Diese Seite erklärt die Bedeutung des Protokolls, das Mastodon und vielen anderen Plattformen des Fediverse zugrunde liegt.**

Mastodon basiert auf dem [ActivityPub](https://www.w3.org/TR/activitypub/) Protokoll. Dabei handelt es sich um eine Empfehlung des W3C.

Mastodon-Instanzen benutzen das Protokoll, um untereinander Nachrichten ihrer Benutzer\*innen auszutauschen. Darüber hinaus kann das Protokoll auch dazu verwendet werden, Aufgaben von Client-Anwendungen (z. B. Smartphone Apps, Desktop-Anwendungen) aus zu erledigen. In diesem Fall nutzen die Clients das Protokoll, um mit der Instanz (dem Server) zu kommunizieren.

ActivityPub nutzt ein ebenfalls vom W3C spezifiertes Datenformat mit dem Namen [ActivityStreams](https://www.w3.org/TR/activitystreams-core/). Mit Activity Stream sind eine Reihe von Konzepten und Inhaltstypen standardisiert, die eine Vielzahl von Anwendungen ermöglichen. Mastodon deckt tatsächlich nicht alle dieser Anwendungen ab.

Dieser Auszug aus der Liste der Objekttypen, die in ActivityStream definiert sind, gibt einen groben Eindruck der Vielfalt:


- `Note`: kurzer Text, typischerweise ein einziger Absatz
- `Article`: Text, der mehrere Absätze enthält
- `Image`: Bild
- `Video`: Bewegtbild
- `Audio`: Tondokument
- `Document`: beliebiges Dokument
- `Page`: Webseite
- `Event`: Ereignis bzw. Veranstaltung
- `Place`: ein physikalischer Ort

So entsteht auf Basis von ActivityPun eine immer größere Anzahl von spezialisierten Anwendungen, die miteinander zumindest in Teilen kompatibel sind. Einige Beispiele:

- [pixelfed](https://pixelfed.org/): Eine dezentrale Plattform für das Teilen von Fotos. Eine mögliche Alternative zu Instagram. Mastodon-Nutzer\*innen können Pixelfed-Profilen folgen und erhalten so die Fotos, die von den gefolgten Pixelfed-Profilen geteilt werden.

- [PeerTube](https://github.com/Chocobozzz/PeerTube) dient dem Teilen von Videos und und bietet damit eine dezentrale Alternative zu Diensten wie YouTube.

- [funkwhale](https://funkwhale.audio/) erlaubt Nutzer\*innen, Musik und Audio zu teilen.

Weitere Projekte listet die Seite [Awesome ActivityPub](https://github.com/BasixKOR/awesome-activitypub).

ActivityPub steht also für ein vielfältiges Ökosystem aus interoperablen Plattformen. Die Möglichkeiten, die dieses Ökosystem bietet, werden in den kommenden Jahren sicherlich rasant wachsen.
