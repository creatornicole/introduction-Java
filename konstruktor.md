# Konstruktur

...spezielle Methode zum Erzeugen von Objekten einer Klasse.

- jede Klasse by default: Standard Konstruktur
  - dieser muss nicht selbst implementiert werden (Ausnahme: eigen erstellte Konstruktoren mit Parametern existieren)
  - besteht aus Namen der Klasse (Name des Konstruktors ist KLassenname) und Klammernpaar ()
    ```java
    public class Mensch {
      //Standard Konstruktor
      public Mensch() {

      }
    }
    ```
- Objekte einer Klasse werden durch Konstruktoren dieser erzeugt
  -> initialisieren neuen Objekte, d.h. stellen (mit Konstruktor) definierten Anfangszustand her

## Zusammenfassung

- Konstruktoren sind spezielle Methoden zum Erzeugen von Objekten einer Klasse.
- Name der Konstruktoren = Name der jeweiligen Klasse
- Arten
  - Standard Konstruktor (Klassenname mit Klammernpaar)
  - selbst definierte Konstruktoren (mit Parametern)
