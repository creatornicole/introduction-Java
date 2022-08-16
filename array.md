# Array

...Datentypen, die zur Speicherung mehrerer Werte eines einzigen Datentyps dienen.

- ist selbst Objekt in Java
- Länge Array nach Erzeugung immer konstant/ nicht veränderbar
  -> Länge gibt an, wie viel Array speichern kann, nicht wie viele Plätze belegt sind
- durchnummeriert, startet mit 0
  -> muss jedoch nicht in Reihenfolge befüllt werden


## Deklaration und Initialisierung

- Deklaration = Festlegung der Aspekte einer Variable
- Initialisierung = Füllen des Arryas mit spezifischen Werten

- Deklaration mit Objektbildung
  ```java
  int[] arr = new int[5];
  ```  
- Deklaration
  ```java
  int[] arr;
  ```  
- Initialisierung (erfolgt durch Zuweisung der jeweiligen Werte)
  ```java
  arr = new int[3];
  arr[0] = 12;
  arr[1] = 23;
  arr[2] = 122;
  ```  
- gleichzeitig Deklaration und Initialisierung
  ```java
  int[] arr = { 2, 23, 123 };
  ```  
## Zugriff
```java
int i = arr[3];
```

## Methoden

|                 Methode                   |                           Erklärung                          |
|-------------------------------------------|--------------------------------------------------------------|
| Arrays.sort(arr)                          | sortiert Array in aufsteigender Ordnung                      |
| Arrays.sort(arr, fromIndex, toIndex)      | sortiert angegebenen Teil des Arrays in aufsteigende Ordnung |
| Arrays.binarySearch(arr, value)           | sucht Array nach Wert ab                                     |
| Arrays.binarySearch(arr, from, to, value) | sucht Array in angegebenen Teil nach Wert ab                 |
| Array.toString(arr)                       | Ausgabe eines eindimensionalen Arrays                        |
| Array.deepToString(marr)                  | Ausgabe eines mehrdimensionalen Arrays                       |

-> um Arrays.binarySearch() zu verwenden, muss Array sortiert sein     
-> Arrays.binarySearch() gibt Index der Stelle, an welcher sich Element befindet, zurück (nicht enthalten -> Index = -1)
-> (Docs)[https://docs.oracle.com/javase/7/docs/api/java/util/Arrays.html]


## Mehrdimensionale Arrays

- es existieren mehrdimensionale Arrays

```java
int[][] zahl = new int[3][5];
```

## Zusammenfassung

- dataype[] arrayName = new datatype[arraySize];
- zur Speicherung mehrerer Werte eines einzigen Datentyps
- Länge konstant nach Erzeugung
- durchnummiert, startet mit 0
