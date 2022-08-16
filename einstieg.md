# Einstieg

Programming Languages exists, because it is easier to understand than machine code that only consists of numbers 0 and 1.

- compiler
  - special program
  - concerts program written in programming language into series of machine code
  - machine code = final (compiled) program that can be executed by the computer
  - final (compiled) program normally strongly depends on processor and operating system (BUT: different in Java!)

## Vom Probelm zum Programm

1. Problem (erkennen)
2. Abstraktion - Problemanalyse (Was muss ich überhaupt machen?), Funktionelle Spezifikation, Algorithmen Entwurf (durch Zusammenfügen einzelner Komponenten)
3. Algorithmus
4. Darstellung - Darstellung in formalisierter Sprache/ Programmiersprache
5. Programm
6. Realisierung - Umsetzung in Elementarschritten
7. Maschine

- in Programmierprozess wird oft konkrete Aufgabe durch vorgegebene Ausgangsdaten beschrieben, für die Lösungsdaten berechnet werden sollen

## Lernprozess

- am Anfang ganz viel Wissen
  -> Gefühl haben, man sei beste/r ProgrammiererIn
- mach etwas Zeit nehmen Erfolge ab, Fortschritt verlangsamt sich, Enttäuschung tritt ein
  = Punkt, an dem die Meisten aufhören

## Tipps und Hinweise

- wichtigste beim Programmieren lernen: Denken dahinter lernen (= Logik)
- das, wwas für uns logisch ist, muss dem Computer immer genau mitgeteilt werden (bspw.: welcher Datentyp)
- Denkfehler sind die am schwierigsten auffindbaren Fehler beim Programmieren
- "Dividing a complex problem into smaller parts makes your program clear to understand and reusable."
- unabhängig von der Programmiersprache muss man zuvor immer überlegen, mit welchen Algorithmus man ein Problem lösen kann und wie man dies in einem Programm umsetzen kann








*NOCH AUSLAGERN:*

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

## Variables

- only methods should be available externally to access data from variables (attributes), data (variables) should be hidden

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
