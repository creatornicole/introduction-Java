# Klassendiagramm

...zur Darstellung von Klassen.

- Modellierungssprache
- Teile (u.a.)
  - Klassendiagramm
  - Sequenzdiagramm
  - Aktivitätsdiagramm

## Basis-Schema

![Klassendiagramm Basisschema](images/klassendiagramm-basisschema.PNG)

| In Schema | Erläuterung |
|-----------|-------------|
| Klassenname | Name |
| Attribute | Liste der Attribute (= Eigenschaften), können auch leer sein, je nach Modifikator nur von Klasse selbst zugreifbar (private) oder von allen externen (public) |
| Methoden | Liste der Methoden (= ausführbare Aktionen) |

## Umsetzung Klassendiagramm in Java

- Attribute
  - Modifikatoren
    - + public
    - - private
    - # protected
  - Name der Variable (Attribut)
  - Datentyp (Als was soll Attribut gespeichert werden?)

  | In Klassendiagramm | In Java          |
  |--------------------|------------------|
  | - a: int           | private int a;   |
  | + b: double        | public double b; |

  ![Attributenangabe in Klassendiagramm](images\klassendiagramm-attribute.PNG)

- Methoden

  | In Klassendiagramm                            | In Java                                               |
  |-----------------------------------------------|-------------------------------------------------------|
  | + Punkt(xWert: double, yWert: double)         | public Punkt (double xWert, double yWert) { ... }     |
  | + Punkt()                                     | public Punkt () { ... }                               |
  | - getX(): double                              | public double getX() { ... }                          |
  | + equals(p: Punkt): boolean                   | private boolean equals(Punkt p) { ... }               |
  | + verschieben(deltaX: double, deltaY: double) | public void verschieben(double deltaX, double deltaY) |

  ![Klassendiagramm Getter Methode](images\klassendiagramm-methode-getter.PNG)
  ![Klassendiagramm Methode](images\klassendiagramm-methode.PNG)

## Zusammenfassung

- Klassendiagramm zur grafischen Darstellung von KLassen
- in Klassendiagramm werden Attribute und Methoden festgehalten
  - Aussage über Zugriff über Modifikatoren
  - Attributen-/Methodenname
  - Aussage über Datentyp
  - bei Methoden evtl. noch Parameter mit Bezeichnung und Datentyp
