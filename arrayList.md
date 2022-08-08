# ArrayList

...Collection-Implementierung für Liste für Elemente eines gleichen Datentyps.

- Anzahl Elemente dynamisch veränderbar
- Import von java.util.ArrayList notwendig
- durnummeriert, wie gewöhnlich startend bei 0


## Deklaration und Initialisierung

```java
ArrayList<Datentyp> Variablenname = new ArrayList<Datentyp>();
```
-> mit Anlegen einer ArrayList werden schonmal 10 Plätze "vorbereitet"
-> im weiteren Programmablauf je nachdem dynamisch angepasst


## Methoden

- add(element)        Hinzufügen Element an Ende des Arrays
- add(index, element) Hinzufügen Element an Stelle index des Arrays und ggf. verschieben der anderen Werte nach hinten
- get(Index)                  Element an Stelle Index aus Array erhalten
- set(index, element)         Hinzufügen eines neuen Wertes zu Array an Stelle index
- remove(index)               Löscht Wert an übergebenen Index und gibt diesen zurück
- clear()                     Löscht die ganze Liste
- size()                      Fragt Größe der ArrayList ab
- toString()                  bei ArrayList von Vornherein definiert
- addAll()                    Zwei Listen vereinigen
- Collections.sort(arrayList) ArrayList sortieren (Comparable für Sortierung einer ArrayList von Objekten)



## Zusammenfassung

- ArrayList<Datentyp> Variablenname = new ArrayList<Datentyp>();
- Speicherung von Elementen eines gleichen Datentyps in Form einer Liste
- Größe ArrayList (= Anzahl Elemente) dynamisch anpassbar
