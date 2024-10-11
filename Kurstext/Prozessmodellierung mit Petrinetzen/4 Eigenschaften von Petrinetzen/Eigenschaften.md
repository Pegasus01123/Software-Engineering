- Formale Definition um Werkzeuge anzuwenden
- Mathematische Schreibweise:
	- ![[Pasted image 20240925085941.png]]
	-  Tupel = besteht aus einer Menge von Stellen, Transitionen, einer Flussrelation und einer Anfangsmarkierung.
	- Menge der Stellen und der Transitionen sind endlich
	- S und T sind disjunkt = keine Stelle S ist gleichzeitig Transition T
	- Flussrelationen sind die Kanten von S nach T und von T nach S
	- Anfangsmarkierungen sind die Marken, die am Anfang an jeder Stelle sind
	- Kantengewichte: wie oft kommt die Kante vor? 
		- Kantengewicht 2 bedeutet 
			- in der Vorbedingung: Zwei Marken müssen anliegen bevor die Transition schaltet
			- in der Nachbedingung: es werden zwei Marken produziert
		- 1 ist default und wird weggelassen
## Schaltregel
- ![[Pasted image 20240925091238.png]]
- aktiv, wenn immer wenigstens so viele Marken anliegen wie das Kantengewicht groß ist.


## Erreichbarkeit
- Eine Markierung ist erreichbar, wenn durch fortgesetztes schalten von Transitionen ich die Markierung erreiche
- ![[Pasted image 20240925093514.png]]
-  ![[Pasted image 20240925094135.png]]

# 13:15

## Zustandsgraph

## Eigenschaften (Verhalten)

## Beschränktheit