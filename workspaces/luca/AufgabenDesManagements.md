# Übergreifende Aufgaben des Managements

- phasenspeziﬁsche Aufgaben
- übergreifende (phasenunspeziﬁsche) Aufgaben

## Risikomanagement
- Auswirkung auf das Projektziel
	- Projektrisiken
	- Produktrisiken
- Kaskadeneﬀekten
	- Durchs Kompensieren von Risiken entstehen neue Risiken
	- Verhindern durch geordnetes und vorrausschauendes Risikomanagement
	
	
### Definition
- Risiko
	- ein mögliches künftiges Ereignis, das zu unerwünschten Folgen führt -DeMarco
	-  ein Ereignis oder eine
		Gruppe von Ereignissen, deren Eintreten negative Auswirkungen auf die Erreichung der
		(Projekt-)Ziele hat. -PRINCE2
- Risikomanagement
	-  systematische Anwendung von Verfahren zur Identiﬁkation und Bewertung
		von Risiken sowie die anschließende Planung und Umsetzung von Maßnahmen zur Risi-
		kobehandlung

### Verfahren
- Identifizieren
	- uhrsächliches Risiken wichtig
	- oft nur die Symptome bekannt
- Analysieren
	- analysieren bewerten und priorisieren
	- untersuchen der Eintrittswahrscheinlichkeit und die zu erwartenden Auswirkungen
- Verfolgen
	- Regelmäßig den Status überprüfen/analysieren auf Änderungen
- Kompensieren
	- Maßnahmen definieren um
		- Eintreten verhindern
		- Auswirkungen beschränken

### Klassen
- Technisch (Anforderungen, Qualität, Technologie)
- Extern (Markt, Kunde, Zulieferer)
- Organisatorisch (Budget, Ressourcen, Abhängigkeiten)
- Projektmanagement (Planung, Kontrolle, Kommunikation)

### Bewertung
- Eintrittswahrscheinlichkeit
- Schadenshöhe
- Risikokennzahl

### Maßnahmen
- siehe Abb. 5.3
- Vermeiden
- Reduzieren der Auswirkungen
- Transferieren
	- wirk nicht in dem Projekt behandelt
- Akzeptieren
	- beobachten
	- Prüfung auf Kompensionsmaßnahmen
	
## Problem- und Änderungsmanagement
- Probleme (Issues) anbestehenden Artefakten
	- Bug Reports
	- Änderungsanforderungen
- Änderungsprozess
	- Innerhalb des Projektteams 
	- Wenn bereits ausgeliefert, möglicherweise durch explizites Gremium
- Erfassung und nachverfolgung
- Vorgehen
	- Anträge erfassen
		- Vorteile, Konsequenzen, Risiken erfassen
	- Bewertung durch Experten
		- möglicherweise extene
		- Besonders wichtig bei zentralen Komponenten
	- Änderungssteuerungsgruppe CCB
		- Teilprojektleiten, andere Abteilungen
		- Besprechung der Anträge
		- Einvernehmliche Annahme
- Änderungsentscheidung
	- Ablehnung
	- Annahme, sofortige Freigabe zur Umsetzung
	- Annahme, spätere Umsetzung zu festgelegtem Zeitpunkt, z.B. Release XY

## Versions- und Konfigurationsmanagement
- Achivierung von Artefakten in verschiedenene Versionen
	- Kennzeichnung
	- Kommentare mit Fertigungsgrad und Beziehungen
- Konfiguration
	- Kollektion von Artefakten die zueinander passen
- Konfigurationsmanagement
	- Rollen und Maßnahmen zur verwaltung und kontrollierten Änderung von Artefakten
	- Verfahren
		- Welche Artefakte fallen darunter
		- Wer ist Verantwortlich
		- Namenskonventionen
		- Releaseplanung
		- Werkzeuge festlegen mit Zugriffsberechtigungen
- Versionsbildung
	- möglicherweise paralleles Arbeiten an Artefakten in Branches
	- anschließendes Mergen
	- Versionierung zwischen mehreren Artekaften möglich mit Lables
	- Entwichlungsstatus kennzeichnen, z.B. Beta
- Es können schnell Probleme entstehen wenn nicht alle mit der gleichen Version arbeiten in z.B. Meetings

## Qualität
- des Softwaresystems
- der erstellten Artefakte
- des Entwicklungsprozesses und eingesetzter Methoden
- Was ist "gute" oder "schlechte" Qualität
	- schlecht messbar
	- Kriterien durch Qualitätsmanagement
- Qualitätsmanagement
	- Planung
	- Lenkung
	- Sicherung
	- Verbesserung
	- Aufgabe aller Führungsebenen mit Projektleitung
- im Unternehmen
	- Beachten der Anforderungen von
		- Kunden
		- Gesetzgebern
		- Mitarbeitern
		- Bild in der Öffentlichkeit
- in Projekten
	- präzise ausrichtung am Projektkontext
- Qualitätsmerkmale für Software
	- Funktionalität
	- Zuverlässigkeit
	- Testbarkeit
	- Effizienz
	- Benutzbarkeit
	- Wartbarkeit
	- Änderbarkeit
- Qualitätssicherung
	- Teil des Qualitätsmanagements
	- Auswahl von Methoden zur Prüfung der Qualiät
	- QS-Handbuch erstellung vom QS-Verantwortlichen
		- mit z.B. StyleGuides für Dokumente
- siehe Abb 5.9
### Reviews
- Überprüfung und Feststellung der Qaulität von Artefakten
- durch Review-Team
- Schritte
	- Durchsicht von Dokumenten
	- Interviews
	- Tests, Simulationen
	- Treffen Meeting
- Vorgehen
	- Planung
	- Kick-Off
	- Individuelle Vorbereitung
	- Review Meetung
	- Überarbeitung
	- Abschluss
- Typen
	- technisches
	- informelles
	- Walkthrough
	- Inspektion
- Weitere
	- Code Review
	- Peer Review durch Experten
	- Audit umfangreich, unabhängige Untersuchung
### Testen
- Automatisiertes Testen
	- Unit-Testing isoliert
	- integriertes Testen auf Systemfunktionalität
	- mit Build Systemen (Continuous Integration)
- Klassen:
	- Regelablauf
	- Grenzfälle
	- Fehlerfälle
- Auch vorheriges schreiben der Testfälle möglich, TDD
- Statische Codeanalyse
	- durch Review oder mit Tools
		- z.B. unerreichbaren Code suchen
	- White-Box
- Dynamische Codeanalyse
	- Unit-Tests
	- in ausgeführter Software
	- Black-Box
	- Ziel: möglichst hohe Überdeckung des Quallcodes
- Formale Analyse- und Beweistechniken
	- in sicherheitskritischen Bereichen
