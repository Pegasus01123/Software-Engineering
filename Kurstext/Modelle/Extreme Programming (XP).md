- von Kent Beck, Ward Cunningham und Ron Jeffries entwickelt
- verzichtet vollständig auf langfristige Entwicklungspläne und weitestgehend auf Artefakte die nicht Code sind
## Struktur:
- Ziel: lauffähiger Code in kurzen Zeitintervallen
- Ein Entwicklungszyklus setzt sich aus mehreren Iterationen zusammen, die wiederum aus mehreren Programmieraufgaben besteht. 
	- Entwicklungszyklus: maximal wenige Monate, am Ende steht eine Produktversion ([Release](Release.md))
	- Iteration: ein und vier Wochen Dauer
	- Programmieraufgabe ([Task](Task)): ein bis drei Tage, manchmal kürzer
- Es muss immer ein Kundenvertreter zur Kommunikation da sein
- Es werden [Taskcard](Taskcard.md)s für Anforderungen erstellt

## XP-Praktiken:
- Testgetriebene Entwicklung
	- es werden erst Testfälle erstellt und danach implementiert
	- unit tests: finden Fehler in Modulen
- Pair Programming:
	- Einer programmiert, der andere begutachtet den Code
	- gemeinsame Diskusionen über eine Aufgabe, Tests
- kontinuierliche Codeintegration:
	- fertiger Code soll möglichst schnell integriert werden
- Refactoring:
	- Änderungen am Code sollen so vorgenommen werden, dass sich die Funktionalität der Software nicht ändert.
## Umgang mit Anforderungen:
- Anforderungen werden in Form von [User Stories](User%20Stories.md) spezifiziert
- [User Stories](User%20Stories.md) sind Ausgang für das [Planungsspiel](Planungsspiel.md) zu Beginn jeder Iteration
- Prioritäten können zu beginn jeder Iteration angepasst werden und Anforderungen hinzugefügt werden.
## Artefakte:
- wenig Dokumentation
## Einordnung:
- entscheidende Rolle ist die direkte Kommunikation
- gut für kleine bis mittlere Teams (2-10 Personen)
- Problem ist die wenige Dokumentation (jemand verlässt das Team, wechsel des Kundenvertreters, Wartungsteam ist anders als Entwicklungsteam)
- unklare Beschreibung der Systemarchitektur
- Vertragsgestalltung kann schwierig werden


