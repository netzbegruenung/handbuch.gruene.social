# Crossposting

**Diese Seite erklärt, wie man eigene Tweets gleichzeitig auf Mastodon veröffentlichen kann.**

Auch wenn wir uns freuen, wenn Nutzer primär Mastodon nutzen, kann es manchmal Gründe geben, die Kommuniation primär über Twitter abzuwickeln und auf Mastodon nur eine Kopie der Tweets dazulassen. Oder man nutzt sogar primär Mastodon und lässt auf Twitter nur noch Kopien der eigenen Toots. Mit dieser Anleitung möchten wir dir zunächst zeigen, wie du Tweets auf Mastodon crossposten kannst.

Die wohl einfachste Form besteht darin, den [Crossposter der Netzbegruenung](https://mastodon-cross.netzbegruenung.verdigado.net/) zu nutzen.

Dort musst du der Anwendung Zugriff auf deinen Twitter-Feed geben (Hinweis zu den geforderten Rechten ganz unten).

Anschließend musst du dich auch bei Mastodon mit deinem Benutzernamen (`name@gruene.social`) anmelden.

## Einstellungen

Wenn du der Anwendung die notwendigen Rechte auf Twitter und Mastodon gegeben hast, musst du nur noch die Einstellung "Teile meine Tweets auf Mastodon" aktivieren.

Empfehlung: Schau dir bitte auch die erweiterten Einstellungen an:

* **Sichtbarkeit deiner auf Mastodon geteilten Tweets**  
Wähle aus, wem deine Tweets auf Mastodon angezeigt werden sollen.
Zur Sichtbarkeit von Mastodon-Toots siehe [Sichtbarkeit von Beiträgen](toots/visibility.md)

* **Retweet-Optionen**  
Entscheide, ob deine Twitter-Retweets
    - gar nicht auf Mastodon erscheinen sollen  
    - mit vorgestelltem "RT @twittername@twitter.com" erscheinen sollen  
    - mit vorgestellten "RT @twittername@twitter.com" und einem Link zum Tweet erscheinen sollen

* **Sichtbarkeit deiner auf Mastodon geteilten Retweets**  
Wähle aus, wem deine Retweets auf Mastodon angezeigt werden sollen.  
Empfehlung: Bei den meisten Mastodon-Instanzen gehört es zum guten Ton, hier "nicht gelistet" auszuwählen

* **Retweet-Optionen**  
Entscheide, ob deine Twitter-Zitate (Tweets von anderen Nutzern, die du beim Retweeten noch kommentierst)
    - gar nicht auf Mastodon erscheinen sollen  
    - mit vorgestelltem "RT @twittername@twitter.com" erscheinen sollen  
    - mit vorgestellten "RT @twittername@twitter.com" und einem Link zum Tweet erscheinen sollen  

* **Sichtbarkeit deiner auf Mastodon geteilten Zitate**  
Wähle aus, wem deine Retweets auf Mastodon angezeigt werden sollen.  
Empfehlung: Bei den meisten Mastodon-Instanzen gehört es zum guten Ton, hier "nicht gelistet" auszuwählen

* **Antwort-Optionen**  
Bei Twitter kannst du auf Tweets antworten.  
Unter diesem Punkt kannst du auswählen, wie mit diesen Antworten beim Übertragen auf Mastodon umgegangen werden soll.
    - gar keine Antworten crossposten  
    - Antworten auf eigene Tweets crossposten (Threads)

* **Twitter Inhaltswarnung**  
Du kannst allen Beiträgen eine Inhaltswarnung vorausschicken. In dem Fall wird der Beitrag zunächst verborgen und muss erst aktiviert werden. Inhaltswarnungen sind auf Mastodon weit verbreitet, wenn es um Themen geht, mit denen viele Menschen nicht ohne Vorwarnung konfrontiert werden möchten.

* **Posts ignorieren, die bestimmte Wörter enthalten**  
Mithilfe einer Liste von Wörtern kannst du Beiträge ausschließen, in denen ein bestimmtes Wort enthalten ist. Oder umgekehrt nur Beiträge crossposten, die eines der Wörter enthalten, die du definiert hast.

## Hinweise zum Crossposting

Nachdem der Crossposter eingerichtet ist, werden alle Tweets innerhalb kurzer Zeit (einige Sekunden, manchmal auch zwei Minuten) nach dem Absenden auch auf deinem Profil unter gruene.social erscheinen.

Wenn du einen Tweet wieder löschst, wird der dazugehörige Toot auf Mastodon dadurch nicht entfernt!

## Eingeräumte Rechte

Der Crossposter erfordert eine Vielzahl an Rechten, was eventuell abschreckend wirkt. Die Anwendung ist auch in der Lage, Toots von Mastodon auf Twitter zu veröffentlichen und benötigt daher zum Beispiel auch das Recht, selber schreiben zu dürfen.

Du kannst der Crossposting-App die Zugriffsrechte jederzeit widerrufen. Du findest diese Funktion
* für Twitter unter "Mehr" -> "Einstellungen und Datenschutz" -> "Account" -> "Apps und Sitzungen" -> "Mastodon-Twitter Crossposter" -> "Zugriff widerrufen" 
* für Mastodon unter "Einstellungen" -> "Konto" -> "Autorisierte Anwendungen", dann hinter "Mastodon Twitter Crossposter" auf "Widerrufen" klicken

Deine Zugangsdaten werden bei der Anmeldung nicht an den Crossposter übertragen, sondern direkt an Twitter bzw. an gruene.social. 
