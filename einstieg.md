# Einstieg

Tipps und Hinweise:
- Das, was für uns logisch ist, muss dem Computer immer genau mitgeteilt werden (bspw. welcher Datentyp).
- Denkfehler sind die am schwierigsten auffindbaren Fehler beim Programmieren


## Java Bäume

## Java Dokumentation

## Java Kommentare

- comments in the code are ignored by the compiler
- comments in the code are often about parts of the code that are difficult to understand
  -> often written before methods to describe nuances in how those methods work


## Java Konstruktur

- kind of class "skeleton" that each new object must match
- is really a method, but with specific features
- every class has a default constructor (by default)
  -> default constructor is eliminated once a contructor with arguments is created
  -> if you need/ want constructor with no-arguments, you will have to declare it separately)
- need constructors to ensure that objects have a valid state

## Klasse

## Klassendiagramm

## Klassenschema

## Methoden

...definieren Funktionalität der jeweiligen Klasse.

- Vielzahl von Kommandos, die spezifische Operationen (mit Objektdaten) ausführen
- Methoden, die Wert zurückgeben, nutzen Keyword "return"
  -> "return" stoppt Methode vom ablaufen
- method overloading
  - overload methods
  - methods with the same name but different parameters
- passed argument are called parameters
  - pass by value -> primitve types are passed to methods by value (copy is created)
  - pass by reference -> objects as parameter are passed by reference

- we use parentheses to pass arguments to the method (also called command)
  -> depending on the value of the arguments, the same method can execute different action
- minimal program must contain at least one class that must include at least one method/ function to get the program running (= main method)
- body of a method consists of commands <=> method is group of commands

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
