
## <font color="228B22">Inkrementelle Modelle</font> 
- große Spannweite von stark sequentiell bis zu iterativ
- Es werden produktiv einsetzbare Teilprodukte ([Inkrement](Inkrement.md)) entwickelt und ausgeliefert
- ausgelieferte Teilprodukte werden nicht überarbeitet
## Entwicklungsprozess:
- zwei grundsätzliche Vorgehensweisen:
	- puzzleförmig:
		- Funktionalität ist nahezu eindeutig in einzelne Teilprodukte aufteilbar
		- Schnittstellen zwischen den Teilprodukten müssen so geplant werde, dass später keine Änderungen mehr nötig sind
	- zwiebelschalenförmig:
		- unterschiedliche Teilprodukte benötigen die selbe Basis
		- jedes Inkrement baut auf dem vorherigen auf.
- Entwicklung der Teilprodukte erfolgt nicht parallel sondern zeitlich versetzt

![Pasted image 20240314110313](Screenshots/Pasted%20image%2020240314110313.png)
## Umgang mit Anforderungen:
- Aufteilung der Anforderungen auf Teilprojekte
- Zentrale Anforderungen müssen zu Projektbeginn soweit klar sein, dass eine Aufteilung auf Teilprojekte möglich ist und Schnittstellen definiert werden können
- Je nach konkretem Modell müssen die Anzahl der [Inkrement](Inkrement.md)e zu Beginn festgelegt werden oder es können im Laufe das Projektes weitere dazukommen
- Modelle mit sequentiellem Charakter erfassen die vollständigen Anforderungen für alle Teilprojekte schon vor Projektbeginn
## Einbezug [Kunde](Kunde.md):
- [Kunde](Kunde.md)n erhalten schnell eine erste einsetzbare Produktversion
- Missverständnisse oder Unklarheiten werden früh sichtbar
- Es können Verträge über Teilprodukte abgeschlossen werden
## Artefakte:
- bei sequentiellem Ansatz eher dokumentenorientiert
- bei iterativem oder agilem Ansatz eher code- und testorientiert

## Auslieferung:
- es werden Teilprodukte ausgeliefert
- es wird schrittweise entwickelt, ausgeliefert und eingesetzt
- jedes [Inkrement](Inkrement.md) bringt neue Funktionen und erweitert die Gesamtfunktionalität


## <font color="228B22">Iterative Modelle</font> 
- auch lauffähige Produktversionen werden noch verändert
- Ziel ist die laufende Verbesserung des [Softwareprodukt](Softwareprodukt.md)es bei jeder Überarbeitung
## Entwicklungsprozess:
- es wird zyklisch entwickelt
- Basisanforderungen werden zu einer ersten Kernversion (Version 0)
- In jedem Zyklus entsteht eine neue, erweiterte oder angepasste Produktversion, welche die vorherige ablöst.
- Einzelne Prozesse sind nur schwach voneinander abgegrenzt
- Entwicklungsteam kann von den Erfahrungen einer Iteration profitieren
- Softwareentwicklungswerkzeuge können gewechselt werden
![Pasted image 20240314113605](Screenshots/Pasted%20image%2020240314113605.png)
## Umgang mit Anforderungen:
- Anforderungsänderungen werden berücksichtigt
- gut geeignet wenn zu Beginn noch nicht alle Funktionalitäten feststehen oder angepasst werden müssen
- Schwierigkeiten entstehen, wenn die Kernversion sich im Verlauf der Arbeit als zu unflexibel für geänderte Anforderungen erweist.
- <font color="#B22222">Schwierigkeit:</font> 
	- Projektfortschritt lässt sich schlecht überprüfen
	- Vertragsgestaltung ist kompliziert
## Einbezug [Kunde](Kunde.md):
- frühzeitige Einbeziehung
- Rückmeldungen des Kunden können bereits in der nächsten Iteration einbezogen werden
- für Rückmeldungen kann die aktuelle Produktversion produktiv eingesetzte werden ([Release](Release.md)) oder es gibt eine Produktvorstellung
## Artefakte:
- Code- oder Testorientiert
- Codeorientiert:
	- am Ende einer Iteration steht Programmcode
- Testorientiert:
	- es liegen eine Menge Testfälle zugrunde

## Auslieferung:


## <font color="228B22">Beispiele:</font>
- [Unified Process und Rational Unified Process](Unified%20Process%20und%20Rational%20Unified%20Process.md)


