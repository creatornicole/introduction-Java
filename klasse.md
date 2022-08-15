# Klasse

...zentrales Element der objektorientierten Programmierung.

- jedes Java-Programm besteht aus mindestens einer Klasse
- ist Sammlung von...
  - Daten (Attributen) (= Was das Objekt hat)
  - Operationen (Methoden), die mit diesen Daten arbeiten (= Was das Objekt kann)
- Attribute und Methoden befinden sich in Klassenrumpf

![](images\klassenaufbau.PNG)

- Klassenname und Dateiname (*.java) müssen immer übereinstimmen!

- _this_ in Klasse = Referenz auf die jeweilige Klasse selbst

## (Objektorientierte) Klassenhierarchie

- Spezialisierung wird in OOP durch eine Klassenhierarchie mit Vererbung realisiert
- Wurzel der Klassenhierarchie in Java: java.lang.Object
- _Object_ hat keine Attribute, aber einige Methoden, u.a.
  - public boolean equal()
  - public String toString()
  - protected Object clone()
  - protected void finalize()
  - public int hashCode()
  - public int getClass()
  -> durch Vererbung besitzt jedes Objekt diese Methoden

## Zusammenfassung

- Java Klassen = zentrale Elemente der OOP
- Sammlung von Attributen (Was hat das Objekt?) und Methoden (Was kann das Objekt?)
- allgemein gültiger Aufbau: [Modifikator] class [Klassenname] { [Klassenrumpf] }
- Klassenname = Dateiname (.java)
- Spezialisierung von Klassen durch Klassenhierarchie mit Vererbung in OOP realisiert.
- Wurzel der Klassenhierarchie ist _Object_
