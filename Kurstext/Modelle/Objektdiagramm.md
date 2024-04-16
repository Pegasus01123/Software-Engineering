- Objekte der Realwelt, Eigenschaften und Beziehungen modellieren
- unterschiedlich Umfangreich
- Objekte ohne Verbindungen
- einzelnes Objekt

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

