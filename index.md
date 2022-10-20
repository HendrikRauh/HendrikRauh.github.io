# Einparkroboter

## ToDo

- [x] Grundfahrgestell bauen
- [x] Motoren testen
- [x] Terminal löten
- [ ] Sensoren testen
- [ ] Getriebe von der Höhe testen
- [ ] Verkabeln
- [ ] Ultraschallsensor Code schreiben [Ultraschall (4pin)](https://funduino.de/nr-10-entfernung-messen) | [Ultraschall (3pin)](https://docs.arduino.cc/built-in-examples/sensors/Ping)


## 4 Motoren

### Verkabelung

[FUNDUINO - L298n](https://funduino.de/nr-34-motoren-mit-h-bruecke-l298n-ansteuern)

Pins: 5 bis 12 mit Motoren

### Software

[Script für 4 Motoren](/Test/Motoren/WechselRichtung.ino)

## 3 Ultraschallsensoren

### Wenn je ein Trigger und ein Echo Pin

Pins: 1 bis 4 & A0 & A1

### Wenn die Sensoren nur ein Output haben

Pins: 2, 3, 4

## LEDs

> **Wichtig:**  Bitte Widerstände nicht vergessen!

Alle Beleuchtung sollte, sofern sie an und ausgeschalten werden soll, an Pin 13 angebracht werden.

Beleuchtung, die immer an sein soll, kann direkt über die 5V vom Arduino betrieben werden.

## Gyroskop

### Warum?

Zum Erkennen, wenn sie das Fahrzeug ausersehen gedreht hat oder sich gerade falsch bewegt.

### Pins

SDA & SCL (+ 5V und GND)
