# Einstieg

Tipps und Hinweise:
- Das, was für uns logisch ist, muss dem Computer immer genau mitgeteilt werden (bspw. welcher Datentyp).
- Denkfehler sind die am schwierigsten auffindbaren Fehler beim Programmieren


## Java Bäume

...sind Datenstrukturen, die hierarchische Strukturen abbilden.

- in Java können Teilbäume angesprochen werden
- einige werden standardmäßig angesprochen/ sind standardmäßig vorhanden
- andere Bereiche müssen explizit mit eingebunden werden: Packages


## Java Packages

...Gruppierung von Klassen, die zu einem gewissen Bereich gehören.

- Unterscheidung
  - Java intern
  - eigene Packages

- Konventionen
  - nur Kleinbuchstaben, Zahlen, Substantive
  - für Internationalisierung: Domainnamen in umgekehrter Reihenfolge
    (bspw.: package de.hsmw;)

## Java Dokumentation






## Java Konstruktur

- kind of class "skeleton" that each new object must match
- is really a method, but with specific features
- every class has a default constructor (by default)
  -> default constructor is eliminated once a contructor with arguments is created
  -> if you need/ want constructor with no-arguments, you will have to declare it separately)
- need constructors to ensure that objects have a valid state


## Klassendiagramm

## Klassenschema



## OOP

## Programmieren lernen

## Programmiersprachen

## Struktogramme

## Understand Arrays

## Variables

- only methods should be available externally, data (variables) should be hidden

## Object Lifecycle

- objects have their own lifestyle
- Java machine allocates memory for created object, but the amount of memory is limited
- object is alive as long as there are references to it
  -> as soon as there are no references, the object dies
  -> Java's built-in garbage collector (GC) takes care of it
- GC
  - works in the background while program is running
  - exists for freeing up memory
  - BUT: so that GC can run properly, you need to keep the "floor" in decent shape and pick up everything that it cannot handle
- mishandlung ressources can lead to memory leaks

## Unterschied _print_ und _println_

...beides zur Ausgabe auf Console.

| print   | ohne Zeilenumbruch  |
| println | mit Zeilenumbruch   |

## Zusammenfassung
