# Access Modifiers

...definieren Sichtbarkeit von Attributen und Methoden - bei bspw. Vererbung immer zu beachten.

- ermöglichen Zugriffskontrolle/ Datenkapselung (information hiding)
  - Welche Methoden und Attribute sind für andere Klassen sichtbar?
  - Welche Methoden und Attribute können von wem aufgerufen bzw. verändert werden?0
- Modifikatoren
  - public
  - protected
  - private
  - "default" (ohne Modifikator)
- Modifikatoren sind optionale (= "default") und können kombiniert werden

- definieren Sichtbarkeiten
  -> Sichtbarkeiten beschreiben die Beziehungen

## Sichtbarkeit für Methoden und Attribute

| Zu sehen von...                | public | protected | "default" | private |
|--------------------------------|--------|-----------|-----------|---------|
| Innerhalb derselben Klassen    |   ja   |    ja     |    ja     |   ja    |
| Klassen im selben package      |   ja   |    ja     |    ja     |  nein   |
| Klassen außerhalb des package  |   ja   |   nein    |   nein    |  nein   |
| Unterklassen im selben package |   ja   |    ja     |    ja     |  nein   |
| Unterklassen außerhalb package |   ja   |    ja     |   nein    |  nein   |

- eingeschränkte Variante von public (noch in Beta!)
  public _sealed_ class Vehicle _permits_ Car, Bike, Bus, Train { ... }

## Zusammenfassung

- Access Modifiers bestimmen die Sichtbarkeit von Methoden und Attributen
- Sichtbarkeiten beschreiben die Beziehungen von Klassen (und deren internen Struktur) zu anderen Klassen
- Access Modifiers
  - public -> höchste Stufe der Sichtbarkeit
  - protected -> Zwischenstufe aus public und "default"
  - private -> nur in Klasse sichtbar
  - ohne Modifikator = "default" -> auch für alle Klassen des package sichtbar
