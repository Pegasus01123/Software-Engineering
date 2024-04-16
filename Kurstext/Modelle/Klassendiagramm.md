- modellierung von Klassen
- eine der wichtigsten Diagrammarten
- stellt Klassen und ihre Beziehungen untereinander dar
- öfter als [[Objektdiagramm|Objektdiagramme]]
- Objektkonstellationen sind nur gültig, wenn sie durch das Klassendiagramm dargestellt werden können
- Beziehungen werden durch eine durchgezogenen Linie angezeigt (Assoziation)
- Zahlen und Sternchen geben an mit wie vielen anderen Objekten die Objekte in Beziehung stehen müssen/können (Multipizitäten)
- Multipizitäten beziehen sich auch die Objekte einer Klasse, nicht auf die Klasse selber

``` nomnoml
#spacing: 75
[Lehrer]1..* -> 2 [Fach]
[Fach]1..10 <- * [Schüler]
```

