# Werkzeuge
Begriff: CASE-Tools ("Computer Aided Software Engineering" Tools)

- Erfassen von Anforderungen
- Modellierung der Architektur
- Codierung [???]
- Testen

Werkzeuge steigern Produktivität nur, wenn:
- Der Einsatz von Werkzeugen sorgfältig erfolgt
- Ein Methodisches Konzept vorliegt
- Eine gewisse Durchgängigkeit (mit wenigen, am besten keinen Medienbrüchen) erreicht wird

Ziel ist es eine Werkzeuginfrastruktur aufzubauen, die die Arbeit von Projektteams optimal unterstützt und den Bedarf jenes umfassend abdeckt.

> Trade-off zwischen der Integration vieler Tools in einem und hochspezialisierter kleiner Tools.

## Projektmanagementwerkzeuge
Dienen der Projektleitung zur Überwachung aller wichtigen Daten und Zahlen für ein oder mehrere Projekte, z.B.:
- Aktuelle Planungsdaten (Erfassung, Speicherung, Aufbereitung)
- Ressourceninformationen
- Trends bei Maßzahlen

Beispiele für PM-Werkzeuge:
- Microsoft Projekt, OpenProj, Merlin, Omni Plan
- Webbbasierte Systeme: Projektron BCS
- SAP, IMB Jazz, Microsoft TFS

Kriterien für die Wahl des richtigen Werkzeugs:
- Verfügbare Hard-/Softwareinfrastruktur
- Verfügbare Lizenzen
- Art / Größe des Projekts

Die am weitesten verbreitete "Projektmanagementsoftware" scheint Excel zu sein. Geeignet für: Kostenplanung/Schätzungen in frühen Phasen, in kleinen Projekten zur Verwaltung von Arbeitsaufträgen.  
Mit zunehmender Projektdauer/-größe nicht mehr konkurrenzfähig.

### Werkzeuge zur Softwareentwicklung:
- Repositories
- Planung / Management
- Browser
- Grafische Editoren
- Strukturorientierte Editoren
- Compiler / Interpreter
- Debugger / Profiler
- Buildsystem
- Refactoring-Tools

#### Repositories
Halten wesentliche Daten des Projekt, wie: Modell, Quellcode, Tests, Anforderungen, Projektdokumentationen

Genaue Festlegung von Regeln nötig: Struktur, Rechte, Bearbeitungsregeln, Verantwortung

##### Beispiele
Kommerziell, Integriert: Team Foundation Server, IBM Jazz  
Offen: CVS, SVN, GIT, Mercurial

#### Entwicklungswerkzeuge
Weite Bandbreite von generischen (general purpose) zu spezialisierten Werkzeugen.

IDEs fassen Texteditoren, Compiler, Linker, Debugger und diverse Hilfsfunktionen wie Quelltextformatierung oder Assistenten zusammen.

Wichtig: Das Management muss für eine ausreichende Schulung des Teams auf immer aktuelle Werkzeuge sorgen. "Hygiene" von IDEs muss gewahrt werden (zahlreiche Add-Ons können Einsatzfähigkeit einschränken).

##### Beispiele
Name | Art | Sprachen
--- | --- | ---
Eclipse | frei | Fokus auf Java
KDevelop | frei | C, C++, PHP
MonoDevelop | frei | Fokus auf .NET
NetBeans | frei | Java, C, C++, Ruby, PHP
Xcode | frei | C, C++, Objective C
Visual Studio | | Fokus auf .NET

#### Modellierungswerkzeuge
UML vs. Domänenspezifische Sprachen (DSL)

### Werkzeuge für Teamarbeit und Kollaboration
- Kommunikationssysteme (Email, Chat, Telefon-/Videokonferenzsysteme)
- Teamkalender
- Repositories
- Entwicklungs-/Buildserver
- Work Item Tracking bzw. Ticket-Systeme (für Tasks, Bugs)

#### Work Item Tracking Systeme
Bugs / Fehler / Anforderungen werden durch Tickets repräsentiert.
Beispiele: Mantis, Bugzilla, Trac
