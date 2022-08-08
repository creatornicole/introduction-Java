# Datentypen

...sind eine Art Bauanweisung für eine Variable.

- legt fest, welche Operationen möglich sind
- legt fest, wie Darstellung der Variablen im Speicher erfolgt
- Unterscheidung Datentypen in "einfache" und selbstdefinierte

## Einfache Datentypen

= Elementare Datentypen = können nicht weiter zerlegt werden
- in Java setzt sich alles aus diesen elementaren Datentypen zusammen

boolean (1 Bit) true/false                                  zwei Zustände, Wahrheitswert
char (16 Bit)   einzelne Zeichen Unicodetabelle in 2 Byte   Zeichenpräsentation
byte (8 Bit)    -128 … 127                                  Ganze Zahl (Darstellung in Zweierkomplement)
short (16 Bit)  -32_768 … 32_767                            Ganze Zahl (Darstellung in Zweierkomplement)
int (32 Bit)    -2147483648 …2_147_483_647                  Ganze Zahl (Darstellung in Zweierkomplement)
long (64 Bit)   -9223372036854775808 …9223372036854775807   Ganze Zahl (Darstellung in Zweierkomplement)
float (32 Bit)  vorzeichenhaftige Fließkommazahl            Fließkommazahl (Darstellung aus Vorkommateil, Dezimalpunkt, Nachkommateil, Exponenten und Suffix (Suffix f oder F kennzeichnet float-Wert))
double (64 Bit) vorzeichenhaftige Fließkommazahl            Fließkommazahl (Darstellung aus Vorkommateil, Dezimalpunkt, Nachkommateil, Exponenten und Suffix)

## Selbstdefinierte Datentypen

...sind Objekte, die sich aus elementaren Datentypen sowie anderen Objekten aufbauen.

## Zusammenfassung

- Datentyp = Art Bauanweisung Variable
- Einfache Datentypen: Wahrheitswert (boolean), Zeichen (char), Ganzkommazahl (byte < short < int < long), Gleitkommzahl (float < double)
- Einfache Datentypen = Elementare Datentypen = nicht weiter zerlegbar
- Selbstdefinierte Datentypen = Objekte, die sich aus elementaren Datentypen sowie anderen Objekten aufbauen
