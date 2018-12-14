### 4.5.x. Tooling

#### Repository

Als zentrale Datenablage wird häufig auf *Repositories* (Versionsdatenbank) gesetzt. Da in vielen Projekten das Repository eine grundlegende Kernkomponente darstellt, ist eine exakte Strukturierung und ein organisierter Umgang erforderlich.

**Struktur**  
Um die wiederfindbarkeit von Daten zu ermöglichen, ist es erforderlich eine (Verzeichnis)Struktur festzulegen.

**Rechte**  
Es muss klar definiert werden, wer Schreib- und Leseberechtigung auf welches Verzeichnis hat.

**Bearbeitungsregeln**  
Es kann erforderlich sein, Regeln für die Benennung von Artefakten festzulegen. Weiterhin kann definiert sein, welche Dateitypen im Repository abgelegt werden dürfen und müssen. Die Festlegung einer Konvention für Check-In-Kommentare / Commit-Messages erleichtert ebenfalls die Arbeit mit dem Repository.

**Verantwortung**  
Es muss klar definiert werden, wer die Verantwortung für das Repository hat. Der Verantwortliche setzt die Einhaltung festgelegter Regeln um. Von Zeit zu Zeit ist das Aufräumen des Repositorys sinnvoll.

##### Repository-Software

Als bekannte und verbreitete Repository-Software ist zum Beispiel das freie aber bereits eingestellte **CVS (Concurrent Version System)**, das ebenfalls freie **Apache Subversion** oder das weit verbreitete, freie und dezentrale **GIT** zu nennen. Das ebenfalls freie und verteilte **Mercurial** kann zum Beispiel Differenzen binärer Dateien erzeugen.

Als kommerzielle Repository-Software findet z.B. **Team Foundation Server** von Microsoft direkte Integration in **MS-Project**. IBM entwickelt mit **IBM Jazz** ebenfalls eine proprietäre Repository-Software. Eine weitere weit verbreitete kommerzielle Versionsverwaltungssoftware ist **Perforce**.

###### Vergleich: Repository-Software

Eigenschaft | CVS | Subversion | GIT | Mercurial | Team Foundation Server | IBM Jazz | Perforce
--- | --- | --- | --- | --- | --- | --- | ---
Lizenz | frei | frei | frei | frei | proprietär | proprietär | proprietär
Dezentral | 🗙 | 🗙 | ✔ | ✔ | 🗙 | 🗙 | 🗙

#### Integration

Eine mögliche Anforderung an Projektmanagementwerkzeuge kann die Integration untereinander sein. So müssen Daten nur an einer Stelle verwaltet werden, können aber in verschiedenen Umgebungen genutzt werden.

**Trello** ermöglicht eine Integration zu den meisten Projektmanagementtools. Ebenfalls lassen sich **Github** und **Gitlab** zu **Jira** integrieren. **MS-Project** ist zu Integration mit Produkten, die nicht von Microsoft stammen nicht geeignet.

Sollte zur Kommunikation auf **Slack**, ein weit verbreiteter Messenger für Projektteams, gesetzt werden lassen sich die genannten Tools bis auf **MS-Project** auch dort direkt integrieren. So können zum Beispiel automatisch Benachrichtigungen zu Statusänderungen bei Tasks versendet werden oder Tasks gar aus dem Messenger verhaltet werden.
