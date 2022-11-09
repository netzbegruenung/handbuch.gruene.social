# Folgen und Folgende

**Hier erfährst Du, wie Du anderen Profilen auf Mastodon folgen kannst und wie sich das auswirkt.**

## Was bedeutet Folgen?

Einem Profil auf Mastodon zu folgen, bedeutet im wesentlichen, die Beiträge zu abonnieren, die von diesem Profil veröffentlicht werden.

Wem Du auf Mastodon folgst, bestimmt ganz wesentlich, welche Inhalte Du auf der Plattform selbst zu sehen bekommst. Zwar bietet Mastodon auch zwei Zeitleisten, die nicht dadurch bestimmt werden, wem Du folgst. Allerdings dürfte die Zeitleiste, die Dir als [Startseite](https://gruene.social/web/timelines/home) angezeigt wird, die wichtigste sein. Denn deren Inhalte werden durch die Profile bestimmt, denen Du folgst.

Wie schon im Abschnitt über das [ActivityPub-Protokoll](mastodon/activcitypub.md) erklärt, kannst Du nicht nur Profilen von einer beliebigen Mastodon-Instanz folgen. Du kannst auch Profilen von anderen Plattformen folgen, sofern diese ActivityPub unterstützen. Twitter unterstützt dieses Protokoll übrigens nicht, und so ist es auch leider nicht möglich, einem Twitter-Account von Mastodon aus zu folgen.

## Ein Netzwerk aufbauen

Folgst Du einem Profil, so wird der oder die gefolgte Nutzer\*in darüber benachrichtigt. Nicht selten dient das der Inhaberin oder dem Inhaber des gefolgten Profils zum Anlass, sich Dein Profil und Deine letzten Beiträge etwas näher anzusehen und Dir ggf. ebenfalls zu folgen. So entsteht, zumindest im technischen Sinne, eine gegenseitige Beziehung. Diese hat zur Folge, dass der oder die betreffende selbstverständlich auch Deine Beiträge zukünftig in der Zeitleiste vorfindet.

Möchtest Du über Mastodon Menschen erreichen, ist es also ratsam, Dich selbst für andere Menschen zu interessieren und diesen zu folgen. Es sei denn, Du bist so bekannt bzw. berühmt, dass sich ohnehin viele für Dich interessieren.

Bei einem Umzug von Twitter ist es außerdem ratsam, Dein neues Mastodon Handle in der Twitter Biografie zu erwähnen. So finden Deine schon vorhandene Follower auf Twitter den neuen Mastodon Account, um Dir auch dort folgen zu können.

## Wie folgt man?

Praktisch geht das Folgen in Mastodon an verschiedenen Stellen:

- In den Zeitleisten: Klicke auf den Namen oder das Bild des Absender-Profils eines Beitrags, um zur Profilseite des Absenders zu gelangen. Nun gibt es mehrere Möglichkeiten:
  - 1. Handelt es sich um ein Mastodon-Profil auf GRUENE.SOCIAL, dann gibt es dort einen Folgen-Button. Diesen klickst Du einfach an. Fertig.
  - 2. Handelt es sich um ein Mastodon-Profil außerhalb von GRUENE.SOCIAL, findest Du ebenfalls einen Button "Folgen" oder "Follow", je nach Spracheinstellung der Mastodon-Instanz. Klickst Du auf diesen, wirst Du aufgefordert, anzugeben, von welchem Profil zu folgen möchtest.
  - 3. Ist das Profil kein Mastodon-Profil, kopierst Du am besten die URL der Seite. Diese gibst Du dann in das Suchfeld auf GRUENE.SOCIAL ein. Als Suchergebnis solltest Du genau einen Personen-Treffer finden, das auf der rechten Seite ein Icon trägt. Ist dieses grau, folgst Du dem Profil noch nicht und kannst es zum Folgen anklicken.

Der nachfolgende Screenshot zeigt ein Suchergebnis mit einem Treffer. Das Icon auf der rechten Seite kann angeklickt werden, um dem Profil zu folgen.

![Aus dem Suchergebnis folgen](img/follow-from-search-result.png)

## Profile zum folgen finden

Profile zu finden, denen man folgen könnte, ist aufgrund der verteilten Arbeitsweise von Mastodon nicht ganz so einfach, wie man sich das vielleicht wünscht. Eine zentrale Suche, wie wir sie von Twitter kennen, gibt es bei Mastodon nicht.

Hier sind ein paar Möglichkeiten, wie Du aktiv nach interessante Profile suchen kannst, denen Du folgen könntest:

- Sowohl die [lokale](https://gruene.social/web/timelines/public/local) als auch die [föderierte Zeitleiste](https://gruene.social/web/timelines/public) enthalten in der Regel auch Beiträge von Profilen, denen Du nicht folgst.

- Das öffentliche [Profilverzeichnis]|(https://gruene.social/explore) von GRUENE.SOCIAL zeigt Profile, die mindestens 10 Folgende haben und deren Inhaber\*innen dem Erscheinen im Profilverzeichnis nicht widersprochen haben. Das funktioniert auch auf anderen Mastodon-Instanzen, wie z. B. [chaos.social](https://chaos.social/explore) oder [social.tchncs.de](https://social.tchncs.de/explore)

- [User Matching in Fediverse](https://distsn.org/user-match.html) ist ein Hilfsmittel, das versucht, Dir Profile vorzuschlagen, die inhaltlich ähnliche Beiträge veröffentlichen wie Du. Hierzu musst Du allerdings schon Inhalte veröffentlicht haben.

- Die Suche nach einem Thema oder Hashtag, entweder auf GRUENE.SOCIAL oder auf einer anderen Instanz.

- Die Tools [Debirdify](https://pruvisto.org/debirdify/) und [FediFinder](https://fedifinder.glitch.me/) durchsuchen die Biografien von Accounts, denen Du auf Twitter folgst, nach Mastodon Handeln und schlagen Dir diese dann vor. So kannst Du leicht Follows von Twitter übernehmen.

## Den Überblick behalten

Mastodon bietet Dir die Seite [Folger_innen und Gefolgte](https://gruene.social/relationships) an, damit Du schnell Profile finden kannst, denen Du folgst und die Dir folgen. Die Seite bietet einige nützliche Funktionen, auf die wir hier näher eingehen wollen.

Unter der Beschriftung **Beziehung** bieten sich auf der Seite drei Filter-Einstellungen:

- [FOLGT](https://gruene.social/relationships): Profile, denen Du folgst.
- [FOLGER_INNEN](https://gruene.social/relationships?relationship=followed_by): Profile, die Dir folgen.
- [BEKANNT](https://gruene.social/relationships?relationship=mutual): Profile, denen Du folgst _und_ die Dir ebenfalls folgen. Also die Schnittmenge aus den oberen beiden.

Leider gibt es bislang keine Liste, die Profile anzeigt, die Dir folgen, denen Du jedoch nicht folgst.

Die Listen lässt sich außerdem nach **Kontostatus** einschränken.

- PRIMÄR: Profile, die nicht umgezogen sind.
- UMGEZOGEN: Profile, die angeben, zu einer anderen Instanz umgezogen zu sein.

Dadurch kannst Du herausfinden, ob Du Profilen folgst, die inzwischen nicht mehr aktiv sind, weil sie zu einer anderen Instanz umgezogen sind. In diesem Fall kannst Du die Profilseite besuchen und herausfinden, wohin das Profil umgezogen ist, um dem neuen Profil zu folgen.

