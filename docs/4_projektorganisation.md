# 4. Projektorganisation
## 4.1. Organisationsformen
## 4.2. Rollen / Teambildung
## 4.3. Management(verfahren) / Aufgaben des Managements
## 4.4. Projekt-/Arbeitsplanung

### 4.4.x. Tooling

Ein Hauptaspekt vieler Projektmanagementwerkzeuge liegt auf dem Abbilden von Arbeitspaketen in sogenannten *Tasks* oder *Issues*. Meist können mehrere Tasks zu *Milestones* zusammengefasst werden.

**Github** etwa unterstützt das Erstellen und Zuweisen dort genannter *Issues*. Sie können mit Labeln versehen werden, um z.B. Dringlichkeit abzubilden. **Trello** erweitert diese Funktionalität um die Möglichkeit ein *Due-Date* festzulegen. In **Gitlab** existiert zusätzlich eine Timetracking-Funktionalität. Auch **Jira** bietet diese Features ebenfalls und ergänzt diese um die Möglichkeit der direkten Priorisierung. All diese Tools erlauben außerdem das granulare Beschreiben von Arbeitspaketen in Checklisten und eine Diskussions-Funktion für Kommunikation betreffend einzelner Tasks. In **MS-Project** existieren die eher abgespeckten *Vorgänge*, die eine ähnliche Funktion erfüllen. Dort können jedoch Abhängigkeiten von Arbeitspaketen im Sinne eines *Projektstrukturplans* abgebildet werden. In **Jira** kann das z.B. über das Abbilden von Tasks in einer Hirachie mithilfe von Sub-Tasks erreicht werden.

``TODO: Ressourcen / Budget``

#### Vergleich: Arbeitspakete in Projektmanagementtools

Funktionalität | Github | Gitlab | Trello | Jira | MS-Project
--- | --- | --- | --- | --- | ---
Arbeitspakete | ✔ | ✔ | ✔ | ✔ | ✔
Zusammenfassen in Milestones | ✔ | ✔ | ✔ | ✔ | ✔
Labeling | ✔ | ✔ | ✔ | ✔ | 🗙
Priorisierung | über Labels | über Labels | über Labels | ✔ | ✔
Zeitplanung (Due-Date) | 🗙 | ✔ | ✔ | ✔ | ✔
Timetracking (inkl. Schätzung) | 🗙 | ✔ | 🗙 | ✔ | ✔
Checklisten | ✔ | ✔ | ✔ | ✔ | 🗙
Diskussion | ✔ | ✔ | ✔ | ✔ | 🗙
Abhängigkeiten | 🗙 | 🗙 | 🗙 | über Sub-Tasks | ✔

Alle genannten Tools ermöglichen eine Darstellung von Arbeitspaketen auf *Kanban-Boards*. Mit **Github** und **Jira** lassen sich diese zusätzlich automatisieren. **MS-Project** bietet als einziges Tool eine integrierte Darstellung als *Gantt-Diagramm* an.

#### Vergleich: Darstellung von Arbeitspaketen in Projektmanagementtools

Funktionalität | Github | Gitlab | Trello | Jira | MS-Project
--- | --- | --- | --- | --- | ---
Kanban-Board | ✔ | ✔ | ✔ | ✔ | ✔
Automatisierung | ✔ | 🗙 | 🗙 | ✔ | 🗙
Gantt-Diagramm | 🗙 | 🗙 | 🗙 | 🗙 | ✔

## 4.5. Projektinfrastruktur

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
