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

## Klassenbeziehungen spezifizieren Objektbeziehungen

![[Pasted image 20240419210537.png]]
- mit jeder Assoziation sind zwei Aussagen verbunden

## mehrere Assoziationen
![[Pasted image 20240419210827.png]]
![[Pasted image 20240419210843.png]]
- bei mehreren Assoziationen zwischen zwei Klassen muss immer entweder assoziationsname oder Rollenbezeichnung vorhanden sein

## Reflexive Assoziationen
- Beziehungen zwischen Verschiedenen Objekten der selben Klasse
![[Pasted image 20240419211300.png]]

## n-äre Beziehungen
- Objekte von mehr als zwei Klassen stehen in Beziehung
![[Pasted image 20240419211416.png]]
## Aggregation und Komposition
- Teil-Ganzes-Beziehung
- Aggregation:
	- unausgefüllte Raute
	- Existenz der Teile ist ohne das Ganze möglich
- Komposition:
	- ausgefüllte Raute
	- Teile können nicht ohne das Ganze existieren 
	- ein Teil-Objekt darf nur mit einem einzigen Ganzes-Objekt verbunden sein
![[Pasted image 20240419212016.png]]

## Assoziationsklassen
- Eigenschaften einer Assoziation können mit den Eigenschaften einer Klasse kombiniert werden
![[Pasted image 20240419212206.png]]

## Generalisierung und Spezialisierung
![[Pasted image 20240419212252.png]]
