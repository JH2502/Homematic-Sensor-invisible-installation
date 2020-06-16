# Homematic Fensterkontakt – verdeckter Einbau

Dieses Projekt bassiert auf der Bibliothek AskSinPP (https://asksinpp.de). Es handelt sich hierbei um einen Nachbau des "Homematic IP Fenster- und Türkontakt – verdeckter Einbau" welcher für den unsichtbaren Einbau im Fenster konzipiert wurde.


## Material

Für das Projekt wird ein Arduino Pro Mini 3,3V, ein 868 MHZ Modul (CC1101), 

| Anzahl | Typ |
| ------------------ | ------------------ |
| 1 | Arduino Pro Mini 3,3V |
| 1 | CC1101 Modul (868 Mhz) |
| 2 | 0805 SMD Widerstand |
| 1 | 0603 SMD LED grün |
| 1 | 0603 SMD LED rot |
| 1 | SMD-Kurzhubtaster, 4,2 x 2,8 mm |
| 1 | Reedkontakt |
| 1 | Magnet 4x2mm |

## Hardware

Alle genannten Bauteile müssen an der dafür vorgesehene Stelle verlöten werden. (Siehe Bilder/Schaltplan)

## Software

Als Sketch findet folgender Anwendung: [HM-SEC-SC](https://github.com/jp112sdl/Beispiel_AskSinPP/blob/master/examples/HM-SEC-SC/HM-SEC-SC.ino)

Für das flashen muss man sich an die allgemeine Anleitung halten: https://asksinpp.de/Grundlagen/02_software.html


## Gehäuse

Für das Gehäuse findet ein 3D Druckteil Anwendung, welches von Thingiverse heruntergeladen werden kann.

[Thingiverse](https://www.thingiverse.com/thing:4462608)


## Aufbau

1. Bauteile auf Platine löten
2. Reedkontakt an vorhergesehene Stelle verkleben
3. Batteriekontakte einkleben
4. Kabel mit Platine verlöten
5. Innendeckel einkleben


**An dieser Stelle vielen Dank an alle Bastler die bei der Entwicklng der Selbstbauprojekte mitgewirkt haben!! Vielen Dank!!**
