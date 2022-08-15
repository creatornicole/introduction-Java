# Methoden

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

## Syntax

![](images\syntax-methode.PNG)

## Arten

| Methodenart    | Erläuterung                                          |
|----------------|------------------------------------------------------|
| Klassenmethode | benötigt kein erzeugtes Objekt, um genutzt zu werden |
| Objektmethode  | benötigt erzeugtes Objekt, um genutzt zu werden      |

-> Objekt- und Klassenmethoden kommen meist gleichzeitig vor

## Zusammenfassung

- definieren Funktionalität der jeweiligen Klasse und der daraus erzeugten Objekte
- Syntax: [Modifikator] [Rückgabetyp] [Methodenname](Parameter) { }
