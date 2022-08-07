# Abstrakte Klassen

...sind Klassen, die als Oberklassen dienen, selbst jedoch nicht zur Bildung von
Objekten herangezogen werden können.

- spezielle Form einer Klasse
- Mittelweg zwischen Interface und vollständig implementierter Klasse
- über Schlüsselwort _abstract_ deklariert

### Verwendung
- Eigenschaften und Fähigkeiten einer allgemeinen Typgruppe definieren.
- abgeleitete Unterklassen spezifiziert diese Eigenschaften und Fähigkeiten schlussendlich

=> Als Basisklassen in einer Klassenhierarchie können abstrakte Klassen grundlegende
Eigenschaften ihrer Unterklasse festlegen, ohne diese bereits konkret zu implementieren.

### Abstrakte Methoden
- bestehen lediglich aus ihrer Signatur, die mit Semikolon abgeschlossen werden
- besitzen keinen Rumpf (fehlende Methodendefinition)

- abstrakte Methode kann nur in abstrakter Klasse stehen
- abstrakte Klasse muss jedoch nicht zwingend eine abstrakte Methode enthalten
  -> können Variablen und vollständig implementierte Methoden enthalten

### Unterklassen
- erbende Unterklassen müssen alle geerbten abstrakten Methoden implementieren
oder sind ebenfalls abstrakt.

## Zusammenfassung
- Oberklasse
- keine Bildung von Objekten
- Eigenschaften und Fähigkeiten eienr allgemeinen Typgruppe definieren
- Spezifikation durch Unterklasse
- Abstrakte Methode => Abstrakte Klasse
- Abstrakte Methode = Deklaration lediglich mit Signatur, ohne Rumpf
