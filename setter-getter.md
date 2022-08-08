# Setter und Getter

- Setter -> Festlegung von Attributen
- Getter -> Erhalten von Attributen einer Klasse

Bsp.:
```java
public class Mitarbeiter {
  private int persnr;

  //Setter
  public void setPersnr(int persnr) {
    this.persnr = persnr;
  }

  //Getter
  public int getPersnr() {
    return persnr;
  }
}
```

## Automatische Erzeugung in Eclipse

Rechtsklick -> Source -> Generate Getters and Setters
