entwickelt von [Booch](Persönlichkeiten%20und%20Organisationen/Booch.md), [Jacobson](Persönlichkeiten%20und%20Organisationen/Jacobson.md) und [Rumbaugh](Persönlichkeiten%20und%20Organisationen/Rumbaugh.md)
- Einheitliche Notation für die Spezifikation und den Entwurf von Softwaresystemen
- 1997 Version 1.0, heute aktuell: Version 2.5.1 von ende 2017
	- Version 2.0 in 2005
		- neu strukturiert
		- allgemeingültiger Objektorientiert
		- zusätzliche Diagrammarten für dynamisches Verhalten
		- formale Beschreibungssprache (OCL)
	- Version 2.5 in 2013
		- Eliminierung von Inkonsistenzen
		- Vereinfachung von Spezifikationen
	- Version 2.5.1 von 2017
		- sieben Strukturdiagramme
			- statische Elemente und Beziehungen
		- sieben Verhaltensdiagramme
			- dynamische Prozessabläufe und Interaktionen
- stellt verschiedene Diagrammarten zur Verfügung
- statische und dynamische Aspekte lassen sich Modelieren
- lässt sich für unterschiedliche [Domäne](Domäne.md)n einsetzen
- ist unabhängig von der Wahl der [Vorgehensmodelle](Vorgehensmodelle.md)
- ist unabhängig von den benutzten [Objektorientierte Programmiersprachen](Programmiersprachen/Objektorientierte%20Programmiersprachen.md)
- es gibt viele verschiedene Tools: von Hilfen bei der Erstellung, bis zur Erzeugung von Quellcode aus UML-Diagrammen
- definiert grafische Symbole für objektorientierte Konzepte
- reine Modellierungsnotation
![[Pasted image 20240322064051.png]]
## Strukturdiagramme
- [[Objektdiagramm]]
- [[Klassendiagramm]]
## Objekte
- kann man sehen oder anfassen (Katze, Tisch...)
- immaterielle Dinge (Konto, Reise...)
- UML:
	- rechteckige Kästchen
	- mindestens einen Objektnamen
	- Objektname unterstrichen
	- Kleinbuchstaben
	- zentriert
	- eindeutig
	- : Katze Objekt vom Typ Katze

``` nomnoml
[<instance> objektname]
```
``` nomnoml
[<instance> pünktchen : Katze]
```
## anonymes Objekt
- irgend ein Objekt eines Bestimmten Typs
- ohne Name
- genau ein Objekt
``` nomnoml
[<instance> : Katze]
``` 
## Klasse
- zeigt den Typ eines Objektes
- Groß geschrieben
- unabhängig von der Existenz der modellierten Objekte
``` nomnoml
[Katze]
```
Darstellung einer Klasse mit Attributen:
``` nomnoml
[Klassenname|attribut1|attribut2]
```
## Beziehungen zwischen Objekten
- Beziehungen werden über eine durchgezogene Linie dargestellt
- Verbindungen können Namen haben
- Verbindungen können eine Leserichtung haben

``` nomnoml
#spacing: 48
#padding: 10
[<instance>weber : Lehrer] -> unterrichtet[<instance>sport : Fach]
[<instance>weber : Lehrer] -> unterrichtet[<instance>biologie : Fach]
[<instance>müller : Lehrer] -> unterrichtet[<instance>sport : Fach]
[<instance>müller : Lehrer] -> unterrichtet[<instance>mathe : Fach]
[<instance>sport : Fach]<- nimmt teil[<instance>nadine : Schüler]
[<instance>sport : Fach]<- nimmt teil[<instance>max : Schüler]
[<instance>biologie : Fach]<- nimmt teil[<instance>max : Schüler]
[<instance>biologie : Fach]<- nimmt teil[<instance>klaus : Schüler]
[<instance>mathe : Fach]<- nimmt teil[<instance>klaus : Schüler]
```



