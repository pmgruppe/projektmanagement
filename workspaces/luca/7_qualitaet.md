# 7. Qualitätskontrolle-/steuerung
## 7.1. Qualität

`Qualität ist der Grad, in dem ein Satz inhärenter Merkmale
Anforderungen erfüllt.`

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
## 7.5. Änderungskontrolle
## 7.6. Reifegradmodelle / Prozessverbesserung
