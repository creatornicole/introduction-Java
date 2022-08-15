# Java Kommentare

...dienen dazu den Quellcode zu dokumentieren.

- werden von Compiler ignoriert
- beinhalten oftmals Beschreibungen zu Teilen des Programms, die schwieriger zu verstehen sind
- auch vor Methoden, um zu beschreiben, wie diese funktioniert

## Kommentararten

| Bezeichnung             | Syntax |
|-------------------------|--------|
| (Ein)Zeilenkommentar    | //     |
| Mehrzeilenkommentar     | /* */  |
| Dokumentationskommentar | /** */ |

Bsp.:

```java
/** Ich bin die Methode addition und addiere die Zahl1 und die Zahl2
* und gebe diese dann auf der Konsole aus.
*
* @param zahl1 Zahl 1 die ich nehme
* @param zahl2 Zahl 2 die ich nehme
*/
public void addition (int zahl1, int zahl2) {
  /*
  * Hier berechne ich das Ergebnis der Zahl1 und Zahl2
  */
  int ergebnis = zahl1+zahl2;
  System.out.println(ergebnis); //Hier gebe ich das Ergebnis aus.
}
```

## Dokumentationskommentare

- auch documentation comment/ doc comment
- normalerweise direkt vor das zu Dokumentierende geschrieben (z.B. vor jeder Methodendeklaration)
- mit Hilfe von Dokumenationskommentaren und javadoc Dokumentaionsdatei erzeugen
  -> javadoc = Werkzeug, welches erlaubt, Dokumentationsdateien automatisch aus mit Dokumenationskommentaren angereicherten Quelldatei zu erzeugen

- aus Dokumenationskommentaren entsteht Java Dokumentation
  1. Einordnung Klassenhierarchie
  2. Allgemeine verbale Beschreibung der Klasse
  3. Kurze Überblicke über...
    - Attribute (Field Summary)
    - Konstruktoren (Constructor Summary)
    - Methoden (Method Summary)
  4. Ausführliche Informationen über...
    - Attribute (FIeld Detail)
    - Konstruktoren (Constructor Detail)
    - Methoden (Method Detail)

## Zusammenfassung

- (Ein)Zeilenkommentar -> //
- Mehrzeilenkommentar -> /* */
- Dokumentationskommentar -> /** */
- Dokumentationskommentare + javadoc = Dokumentationsdatei
