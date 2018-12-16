# 7. Qualitätskontrolle-/steuerung

Sicherstellung der Qualität des Softwareprodukts

konstruktive Qualitätssicherung
- systematische und vorausschauende Entwicklungsschritte sicherstellt
analytische Qualitätssicherung
- die nach Fertigstellung das (Teil-)Ergebnis eines Entwicklungsabschnitts auf seine Qualität überprüft

Systemfehler Ursachen:
- Fehler in der Entwicklung (Spezifikation, Entwurf, Programmierung)
- Fehler in den Daten, den Nachrichten oder in den Parametern
- Fehler in Algorithmen (Überlauf der Arithmetik, Speicherüberlauf)
- Geräte- und Hardwarefehler
- Inkonsistenzen in der Konfiguration

Nutzerfehler sind keine Systemfehler.

## 7.1. Definition: Qualität

`Qualität ist der Grad, in dem ein Satz inhärenter Merkmale Anforderungen erfüllt.`

Die Qualität eines Softwaresystems bezieht sich auf die Anforderungen und deren Umsetzung in Projekt.
Viele der Anforderungen lassen sich nicht in gut oder schlecht unterteilen, da sie nicht messbar sind.
Auch zwischen Projekten ist ein Vergleich selten möglich, da sich diese zu stark unterscheiden.
Somit müssen durch das Qualitätsmanagement die Kriterien möglichst genau festgelegt werden.

## 7.2. Metriken und Messungen

### Qualitätsmerkmale für Software
- Funktionalität
- Zuverlässigkeit
- Testbarkeit
- Effizienz
- Benutzbarkeit
- Wartbarkeit
- Änderbarkeit

Dies ist eine projektübergreifende Aufgabe der Projektorganisation sowie des Managements. Hierbei gibt es eine allgemeine Bewertung und Verbesserung des Standes, der Qualität usw. für ein zukünftig besseres Zusammenarbeiten untereinander.

Zur Beurteilung ist es wichtig, Kennzahlen und Maßfunktionen (Metriken) einzuführen. In der Softwarentwicklung sind es überwiegend analoge Kennzahlen, die es erlauben, die Qualität und Leisungsfähigkeit eines Produkts sowie des dazugehörigen Entwicklungsteams zu messen. Die Verfolgung muss immer einem Zweck dienen.

### Sichten auf Metriken
Metriken bestimmen bestimme Eigenschaften einer Software bzw. eines Einwicklungsprozesses im Hinblick darauf, ob diese Erfüllt werden. Diese kommen entweder von dem Kunden oder dem Management selbt.
Die wesentlichen Sichten auf Software und Softwareprozesse sind wie folgt:

- Managementsicht
- Entwicklersicht
- Kundensicht

Für jede Sicht gibt es eine bestimme Menge an Metriken, welche aber eines gemeinsam haben: Sie bilden eine Eigenschaft im Sinne einer Messbaren Größe auf eine Zahl ab.

### Messbare Merkmale von Software und Softwareprozessen
Die Hauptaufgabe von Metriken ist es, Eigenschaften von Projekten sichtbar, vergleichbar und veranschaulich darzustellen.

Typische Eigenschaften sind:

- Umfang und Leistung
- Effizienz
- Qualität

Typische Kennzahlen für Entwicklungsprozesse sind:

- Produktivität
- Kommunikationsintensität
- Termintreue

#### Aussagekraft von Metriken am Beispiel LOC
In der Regel lassen Programmiertechnische Aufgabenstellungen in sehr verschiedenen Arten und Längen lösen.
Hierbei betrachtet man nicht nur die LOC (Lines of Code) sondern auch die Komplexität dieser. So ist es unausreichen nur die Länge zu betrachten und die Aussagekraft anhand dieser zu bestimmen.

#### Metriken als Basis für die Messung der Produktivität
Eine geschickte Methode zur Messung des Leistungsumfang liefert die "Function Point Methode".
Hierbei wird der Umfang durch Ermittlung funktionsspezifischer Kennzahlen bestimmt. Hier werden zwar nur ungefähre Ergebnisse, aber diese genügen meistens dem Anspruch.

#### Werkzeugunterstützte Erfassung von Kennzahlen
Es gibt Software zur Erfassung von Kennzahlen. Dadurch lassen sich diese über einen längeren Zeitraum einfacher protokollieren und darstellen.

### Prinzipielles zu Metriken
Metriken sollten immer einigen dieser Anforderungen genügen:

- Objektivität
- Messgenauigkeit
- Vergleichbarkeit
- Nützlichkeit

### Metriken für Produkte
Produktmetriken definieren die Software anhand von Größen wie z.B.:

- Umfang
- Komplexität
- Design
- Performanz
- Qualität

### Metriken für Prozesse
Prozessmetriken drücken die Performanz des Entwicklungsprozesses aus.
Hierbei können bspw. folgende Kennzahlen erfasst werden:

- Zeitbedarf für Fehlerkorrekturen
- Zeitbedarf für Einarbeitung von Änderungen
- Prozessreife

### Metriken für Projekte
Projektmertriken beschreiben die Performance des Projekts an sich.
Folgende Kennzahlen ergeben sich bspw.:

- Termintreue
- Kosten - und Ressourcenverbrauch
- Produktivität

Werden Wertebereiche verlassen, so muss das Management eingreifen uns sofort vereinbarte Steuerungsmaßnahmen einleiten, solche wie:

- Termine
	- Pufferzeiten für Termine
- Kosten
	- Puffer für den Verbrauch des Budgets#
- Umfang
	- Abstriche vom vereinbarten Funtionsumfang

Werden diese Puffer überschritten, so muss die nächsthöhere Entscheideungsebene eingreifen, sodass unverzüglich Entscheidungen zur Problemlösung getroffen werden.

## Metriken erfassen und auswerten
Laut Walmüller gibt es zwei Erkenntnisse aus seinen Erfahrungen:

1. Was nicht vorher gemessen wurde, kann nicht gesteuert oder geregelt werden
2. Nicht so genau wie möglich messen, sondern so genau wie nötig

### Der Goal-Question-Metric Ansatz
GQM ist eine Methode zur Durchführung zielorientierter Messungen.
Dabei geht man von Messzielen und benötigten Informationen aus und leitet daraus Metriken ab.

### Software Cockpits
Heutzutage übernehmen Dashboards die Aufgabe, den Projektstatus und Trends zu ermitteln, die auf womöglich später auftretende Probleme hinweisen können.
Sie sammeln, agregieren und visualisieren die Daten aus verschiendenen Datenquellen und geben dem Management einen guten Überblick auf das Projekt.
Dashboards sind dabei meist sehr flexibel und stark konfigurierbar um die gewünschten Informationen zu erfassen und darzustellen.

## 7.3. Methoden zur Qualitätssicherung
### Reviews
Zur Überprüfung und Feststellung der Qualität von Artefakten werden unteranderem Reviews durchgeführt.
Dieses wird durch ein vorher festgelegtes Review-Team durchgeführt.
Diesem Team werden die einzelnen Prüfobjekte zugeordnet, die von denen anschließend untersucht werden.
In einem **Review Meeting** werden die Ergebnisse der Prüfung diskutiert und gegebenenfalls Maßnahmen zur Behebung festgelegt.
Nachdem die Überarbeitung abgeschlossen ist, werden die Ergebnisse erneut vom Review-Team geprüft.

#### Typen
- **Technisches Review**: Finden von Fehlern in technischen Dokumenten wie Architekturdokumente
- **Informelles Review**: Technisches Review in informeller Form
- **Inspektion (Walkthrough)**: Diskutieren von Fehlern und Lösungsansätzen für grundsätzliche Fehler und Probleme
- **Code Review**: Inspektion von einzelnen Code-Ausschnitten
- **Peer Review**: Review von Experten, die sich im falle eines **Blind Reviews** nicht kennen oder zuordnen lassen.
- **Audit**: Untersuchen vom aktuellen Stand des Projektes von externen Auditoren

### Testen
Ein weiterer wichtiger Schritte in der Qualitätssicherung von Software ist der Softwaretest.

#### Implementation und Test
In der Implementierung wird der Systementwurf aus programmiert. Ausgangspunkt dafür ist die Systemarchitektur mit Datenmodell und Komponentenspezifikation.

Qualitätsmerkmale des Codes:
- die Wahl (Namensgebung) für Identifikatoren (Variablen, Klassen etc.)
- die Vermeidung risikobehafteter Sprachelemente
- die Dokumentation
- die Form/Schreibweise/Stil der Codierung

Vorteile:
- für die Zukunft, gute Lesbarkeit
- weniger Fehleranfällig
- Überprüfbarkeit

Die Codedokumentation ist ein wichtiger Bestandteil des Quellcode. Die Dokumentation soll direkt zum Codier Zeitpunkt erstellt und gepflegt werden. Die Dokumentation erst im Nachhinein zu erstellen, ist meist aufwendig und gibt die Überlegungen bei der Implementierung oft nicht richtig wieder.

- Spezifikation (formal oder informell) mit
	- Vor- und Nachbedingungen eines Funktionsaufrufs
	- Rolle und Typ von Parametern
	- Fehlerfälle
	- Fehler-/Ausnahmebehandlung
- Angabe der durch eine Funktion aufgerufenen weiteren Funktionen
- Laufzeiten und Speicherbedarf

#### Integration und Test

Da mehrere Personen an einem Projekt an verschiedenen Stellen programmieren, müssen diese auch irgendwann zusammengefügt werden. Da sollte es aber so sein kleine "Teil-projekte" nach und nach zusammenzufügen und keine "Big-Bang-Integration" durchzuführen.

Vorteile:
- Fehlerlokalisierung ist einfacher, wenn in ein bereits ausgetestetes Teilsystem, ein weiter Teilsystem integriert wird
- es kann mit einer Integration begonnen werden, wenn Teilsysteme fertig sind

Bei der Integration werden ebenfalls Fehler gefunden, diese zu lokalisieren ist oft schwieriger, da es:
- Architekturfehler
- Teilsystem- oder Modulfehler sein können

#### Wartung
Die Wartung wird abgetrennt vom Projekt und wird daher auch nicht mehr als Projekt gesehen. Sondern als langfristige und nicht abschätzbare Zeit als Aufgabe gesehen.

### Statische Codeanalyse
Bei der auch **White-Box** genante Vorgehensweise liegt dem Test der Quellcode des Programms vor.
Dieser wird nach möglichen Programmierfehlern, wie zum Beispiel unerreichbarem Code, durchsucht.

### Dynamische Codeanalyse
Unter dynamischer Codeanalyse fallen Tests, die den Programmcode ausführen.
Eine häufig verwendete Methode ist das **Unit-Testing** bei dem einzelne Softwareeinheiten geprüft werden.
Der Quellcode des Programmes muss dem Test hier nicht immer vorliegen.

### Formale Analyse- und Beweistechniken
Werden besonders sicherheitsrelevante Algorithmen ausgeführt ist es gegebenenfalls möglich diese formal zu analysieren und zu beweisen.

#### Automatisiertes Testen
Diese Tests sollten automatisch Durchgeführt werden, um die gewünschte Funktionalität auch nach größeren Änderungen gewährleisten zu können.
Durch Build-Systeme werden diese beispielsweise nach jedem Commit ausgeführt.
In den Tests wird zwischen drei Klassen unterschieden:

- **Regelablauf**: Testen des Programmablaufes bei gültigen Eingaben.
- **Fehlerfälle**: Was passiert bei fehlerhaften Eingaben, wird hier richtig reagiert?
- **Grenzfälle**: Hier werden Tests mit Eingabewerten durchgeführt, die "gerade noch" gültig sind.

## 7.4. Aufwandskontrolle
In einem Projekt ist der erforderliche Aufwand und an diesem Aufwand gekoppelt das Projektbudget.
Daher ist die Überwachung des Aufwands und das Verhältnis von verbrauchtem zu geplanten Aufwand wichtig zu beobachten.

### Aufwandserfassung
Um einen Soll-/Ist-Vergleich für die Aufwandserfassung durch zuführen zu können, muss die verbrauchte Zeit erfasst werden.
Die Projektmitarbeiter dokumentieren ihre geleistete Arbeit z.B. auf Stundenzetteln.
Dieser wird erfasst und ausgewertet, meist in Datenbanken.

Die Erfassung des Aufwands ist meist lästig für die Mitarbeiter.
Da das selbst wieder mit Aufwand verbunden ist.

### Aufwandskontrolle
Hier geht es um wie viel vom geplanten Aufwand zu einem Zeitpunkt im Projekt verbraucht wurde und wie viel noch zur Verfügung steht.
Damit kann man Symptome und Ursachen ermitteln

Zu hoher Aufwandsverbrauch
Mögliche Ursachen für einen zu hohen Ressourcenverbrauch sind:
- Unterschätzung des Projektaufwands (Gefährdung von Terminen und Budget)
- Unzureichende Qualität der Mitarbeiter (mangelnde Qualifikation, Motivation, Produktivität)
- Leerlauf der Mitarbeiter durch unklare Aufgabenstellung

### Kostenerfassung und -kontrolle
Die Kostenerfassung erfolgt durch:
- Tätigkeitsberichte für Personalkosten
- Kosten für Unteraufträge
- Interne Berechnung für Materialkosten, Dienstleistungen und ähnliches

## 7.5. Änderungskontrolle
Für den Erfolg eines Projekts ist eine sehr konsequent ausgeführte Änderungskontrolle wichtig. Die Ziele sind die Arbeitsgrundlagen und abgenommenen Artefakte nicht ohne Zustimmung und Wissen der anderen Beteiligten zu ändern und darüber hinaus willkürlich und nicht ausreichend gerechtfertigte Änderungen an gemeinsamen Arbetsgrundlagen zu vermeiden.

Gegenstand der Änderungskontrolle sind alle Ergebnisse der Entwicklungszyklen, insbesondere:

- Systemanforderungen
- Architektur- und Schnittstellenfestlegungen
- Komponentenanforderungen
- Testdaten
- Code

Diese Gegenstände der Änderungskontrolle oder Teile werden nach ihrer Fertigstellung zum Ende der entsprechenden Entwicklungsabschnitten im Rahmen der Qualitätssicherung gemäß Vorgaben kritisch überprüft. Damit ist dies eine gültige Arbeitsgrundlage, die nicht "so einfach" geändert werden darf. Falls Änderungen gemacht werden müssen, müssen diese ab dem Zeitpunkt der Fertigstellung von allen Beteiligten der Änderungsgruppe genehmigt werden.

### Änderungsforderungen und Änderungsentscheidungen
- Änderung der Anwenderanforderungen
- Unklarheiten in den Anforderungen oder im Entwurf
- Fehler im Entwurf oder im Softwaresystem
- Nichterfüllung der Anforderungen (fehlende oder fehlerhafte Funktionalität)
- Qualitätsmängel (hinsichtlich Tests, Leistung, Stabilität)
- Optimierungsbedarf oder -optionen (Performance, Skalierbarkeit)

### Konfliktpotenzial
Durch mehrmalige Änderungen kann es leicht zu Konflikten im Team kommen.
Der Arbeitsmoral sinkt, da das Projektteam den Eindruck erweckt, dass es sich gar nicht lohnt etwas fertig zu machen.

## 7.6. Reifegradmodelle / Prozessverbesserung
Die Projektfähigkeit ist ein wichtiger Bestandteil zur Einschätzung des Erfolges eines Projekts. Oft aber wird diese unterschätzt, was ein höheres Risko für Projekte bedeutet.
Um einen nachvollziehbaren Entwicklungsprozess darzustellen, nutzt man Reifegradmodelle.
Bei Reifegradmodellen geht man davon aus, dass die Prozessqualität Einfluss auf die Produktqualität hat.

### Der kontinuierliche Verbesserungsprozess
Der kontinuierliche Verbesserungsprozess (KVP) ist die Grundlage für die meisten Prozessverbesserungsprogramme.
Der KVP zielt darauf ab, eine Verbesserung in kleinen aber stetigen Schritten vorzunehmen. Da der KVP dadurch ein Hauptbestandteil eines Unternehmens ist, ist die Bereitschaft der Unternehmens eine unerlässliche Voraussetzung.

Der KVP basiert auf dem sog. "Demingkreis", auch "PDCA-Zyklus" genannt.

Die Bedeutung sieht wie folgt aus:

- **P**lan
	- Hier wird ein potenziell Verbesserungswürdiger Prozess untersucht und ein passendes Konzept entwickelt
- **D**o
	- Das Konzept wird wie ein Prototyp erst nur grob umgesetzt
- **C**heck
	- Der Prototyp wird evaluiert. Ist diese positiv, wird der Prozess für die Kompletteinführung freigegeben
- **A**ct
	- Der Prozess wird nun breiter eingeführt und weiterhin bewacht.

### CMMI
Das Softwarereifegradmodell CMMI (Capability Maturity Model Integration) ist eine etablierte Methode um die Fähigkeit eines Unternehmens in Hinsicht Software zu entwickeln zu bewerten.
Beim CMMI werden dabei durch Fragebögen und Interviews die relevanten Punkte der Softwareentwicklung analysiert und bewertet. Hauptzweck dabei ist es, Prozesse zu bewerten und Schwächen aufzudecken.

#### Bestandteile des Reifegradmodells CMMI
CMMI setzt sich aus den Bestandteilen Prozessgebiete, Fähigkeitsgrad und Reifegrade zusammen.

##### Prozessgebiete
Um am Markt erfolgreich zu bleiben, müssen Unternehmen eine Reihe von Erfolgsfaktoren beachten.

Diese lauten:

- Requirements Engineering
- Nutzerorientierung
- Vorkehrungen zur Systemintegration
- Geschäftsprozessoptimierung
- Migrationsstrategien

Zu jedem der Punkte sollte ein Unternehmen ein bestimmten Lösungsansatz besitzen.
Ein Prozessgebiet ist hier eine Zusammenfassung von gleichen Praktiken zu einem Themenbereich.
Dabei gibt es mehrere Prozesse, wobei diese mehreren Prozessgebieten zugewiesen werden können.

Prozessgebiete selbt sind dann wieder untergeordnet in drei Prozessgebietskomponenten (PGK):

1. Erforderliche PGK
2. Erwartete PGK
3. Informative PGK

##### Fähigkeitsgrade
Bezeichnet den Grad der Institutionalisierung eines Prozessgebiets, also ob Aufgabe definiert und auch aktiver Teil der Arbeit sind.

Hierbei gibt es vier Fähigkeitsgrade:

- Grad 0 (unvollständig)
	 - Gibt ein Vorgehen an, welches nur teilweise oder noch gar nicht definiert ist
- Grad 1 (durchgeführt)
	 - Bezeichnet einen Prozess, welcher alle Zielstellungen erfüllt
- Grad 2 (geführt)
	 - Bezeichnet einen Prozess, der nach Leitlinien durchgeführt wird und dem alle Stakeholder integriert sind
- Grad 3 (definiert)
	 - Ein Prozess wird ähnlich wie in Grad 2 kontrolliert durchgeführt. Zusätzlich wird dieser durch ein Tailoring aus einem Standardprozess abgeleitet

##### Reifegrade
Reifegrade bestimmen die Leistungen des Unternehmen selbt.

CMMI differenziert hierbei in fünf Reifegrade:

- Level 1 (ungeregelt)
	 - Keine Vorgaben und Anforderung an die Entwicklung und Organisation
- Level 2 (geordnet)
	 - Grundsätze sind etabliert und die Arbeit wird so angegangen, dass auch weitere Projekte erfolgreich geführt werden können
- Level 3 (standardisiert)
	 - Zusätzlich ein festes Vorgehen in Projekten, bspw. eine Basis eines Standardprozesses
- Level 4 (organisiert)
	 - Zusätzlich wird die Projektperformanz der Projekte gemessen
- Level 5 (optimierend)
	 - Zusätzlich wird die Arbeit auf Basis von Messungen und Metriken durchgehend optimiert

#### CMMI-Derivate
CMMI besteht aus einem Grundmodell und vier Derivaten:

- CMMI-DEV (Verbesserung von Entwicklungsprozessen für Entwickler)
- CMMI-ACQ (Bewertet Prozesse, die sich mit dem Management von Zuliefern und Beschaffungsketten befassen)
- CMMI-SVC (Eignet sich für Unternehmen welche hauptsächlich Dienstleistungen anbieten)
- People CMM (Untersucht Prozesse, welche sich auf den Umgang mit den eigenen Mitarbeiten beziehen)

#### CMMI Appraisals
Zur Bestimmung der Reife werden Appraisals oder auch Assessments durchgeführt. CMMI wird dabei von der Appraisal-Methode SCAMPI (Standard CMMI AppraisalMethod for Process Improvement) begleitet.

SCAMPI bestimmt hierbei drei Appraisal Typen:

- Klasse A
	 - Größtes Appraisal, ist sehr genau, benötigt aber auch sehr viel Aufwand für die Durchführung
- Klasse B
	 - Weniger Umfangreiches Appraisal, dient dazu, Stärken und Schwächen des Prozesses zu analysieren
- Klasse C
	 - Appraisal mit dem wenigstem Aufwand, wird hier aber öfter durchgeführt und dient grob der Beobachtung und Kontrolle eines laufenden Prozessverbesserungsprogramms

### Weitere Ansätze zur Prozessverbesserung
Weitergehend gibt es viele weitere Ansätze, einige Verstehen darunter die Sammlung und Strukturierung von prozessrelevantem Wissen und andererseits wird hier das Wissen von ähnlich orientierten Unternehmen gesammelt und analysiert.

#### ISO 9000'er Serie
Das ISO-9000 Normenwerk legt einen organisatorischen Rahmen für die Qualitätamanagementsysteme und Qualitätssicherung fest.
Unternehmen können sich hierbei normalerweise nach ISO 9000 zertifizieren lassen.

#### SPICE
SPICE (Software Process Improvement and Capability Determination) ist eine weitere Möglichkeit, den Reifegrad zu bestimmen.

Wie auch bei CMMI gibt es Reifegradstufen

- Stufe 0 (unvollständig)
	- Prozess noch nicht umgesetzt
- Stufe 1 (durchgeführt)
	- Prozess erfüllt an sich seinen Zweck
- Stufe 2 (gesteuert)
	- Prozess wird ausreichend geplant, überwacht und gesteuert und eine Qualitätssicherung wurde etabliert
- Stufe 3 (etabliert)
	- Projekte nutzen ein etabliertes Standardvorgehensmodell welches angepasst werden kann
- Stufe 4 (vorhersagbar)
	- Gibt an, dass Prozesse gemessen werden können, um die Prozessleistung zu bestimmen
- Stufe 5 (optimierend)
	- Hier werden durchgehende Prozessverbesserungen vorgenommen

#### Six Sigma
Six Sigma ist eine statische Methode zur Messung, Analyse und Verbesserung von Geschäftsprozessen.
Hauptsächlich ist die Erreichung von Zielen die auf Basis von Kennzahlen der Unternehmen und auf Basis von Kundenwünschen definiert.
Kernprozess ist der "DMAIC"-Zyklus (Define - Measure - Analyze - Improve - Control).
