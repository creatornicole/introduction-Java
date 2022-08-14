# JVM und JDK und JRE

- es wird immer zwischen JDK und JRE unterschieden
- ab Java 11 wurde JRE aktiver in JDK integriert

|            JVM                                                                     |            JRE                                                    |            JDK                                   |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------|--------------------------------------------------|
| Java Virtual Machine (Teil von JRE)                                                | Java Runtime Environment (inkl. JVM)                              | Java Development Kit                             |
| ermöglicht Ausführung eines gestarteten Java Programms in virtuellen Maschine (VM) | beinhaltet alles, um Java-Programme auszuführen/ laufen zu lassen | gebraucht, um selbst Java-Programme zu schreiben |
| Schnittstelle zur Maschine und Betriebssystem                                      | kann nicht verwendet werden, um neue Programme zu erstellen       | ermöglicht Programme zu erstellen                |
| => Ausführung Byte-Code                                                            | => Java-Programme laufen lassen                                   | => Java-Programmierung                           |

## Funktionsweise JVM

1. Java-Compiler (Programm) übersetzt Java-Programmtext in plattformunabhängigen Bytecode
2. Erzeugter Bytecode wird von plattformabhängigen JVM ausgeführt
3. Erzeugte Bytecode-Dateien (.class) während Laufzeit in lokale Maschinensprache übersetzt

- Virtuelle Maschine arbeitet wie Interpreter
- Java-Interpreter führt den Bytecode aus und simuliert einen "virtuellen Prozessor"

## Zusammenfassung

- JVM (Java Virtual Machine) -> Ausführung Java-Bytecode -> ermöglicht Plattforunabhängigkeit von Java
- JRE (Java Runtime Environment) -> Ausführung Java-Programme
- JDK (Java Development Kit) -> Java-Programme schreiben

- Java-Programmtext wird in plattformunabhängigen Bytecode übersetzt
  -> Bytecode von plattformunabhängigen Java VM (JVM) ausgeführt
  -> und während Laufzeit werden Bytecode-Dateien (.class) in lokale Maschinensprache übersetzt
- Java-Quellcode von Java-Compiler in "Byte-Code" (= maschinenunabhängiger Zwischencode) übersetzt und dann vom jeweiligen Interpreter ausgelegt.
