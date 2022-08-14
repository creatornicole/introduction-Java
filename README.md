# Introduction to Java

Helpful documents for getting started with Java (German version).

## Order to learn

## Gründe für Java

- ist einfach und leicht zu programmieren
- ist einfach und leicht zu lernen, da objektorientiert d.h. mit Java ist Beschreibung von Objekten möglich
- interpretiert Java-Bytecode und ist somit plattformunabhängig
  -> Java führt Code nicht direkt auf dem System aus, sondern durch eine virtuelle Maschine (JVM)

## Wichtige Kommandos
|                        Zweck                             |         Kommando          |
|----------------------------------------------------------|---------------------------|
| Programmübersetzung (also xyz.java -> xyz.class)         | javac nameOfJavaFile.java |
| Programmausführung                                       | java nameOfJavaFile       |
| Quellcode-Analyse (Disassemble) (also Anzeige Byte-Code) | javap -c nameOfJavaFile   |

## Java-Programmarten
|                | Stand-Alone-Anwendungen |             Applets              |                    Servlets                    |
|----------------|-------------------------|----------------------------------|------------------------------------------------|
| Anwendung      | eigenständige Anwendung | Bestandteil eines HTML-Dokuments | Java-Klassen                                   |
| mit/ ohne GUI  | mit und ohne möglich    | mit                              | Ausführung auf speziellen Java-fähigen Servern |
| Hinweise       |                         | VERALTET!                        | Bsp.: Tomcat, Websphere, JBoss                 |

## Einrichtung "Java-Pfad"

- ist Pfad unter den Java Dokumente speichert
- dieser Pfad sollte nicht editiert werden
