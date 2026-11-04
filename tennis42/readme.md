## Tennis for two for xy oscilloscope

### Notes

Historic background: https://www.m-e-g-a.org/research-education/research/t42-tennis-for-two/

AVR Implementierung: http://www.evilmadscientist.com/2008/resurrecting-tennis-for-two-a-video-game-from-1958

Transcript mit ChatGPT in pdf Datei bis v8. Danach weitere Versuche die Oszi Darstellung zu verbessern.

Alle Versionen bis zur "fertigen" Version v11 sind hierher kopiert.

Hier wurde das Ursprungsprojekt in eine Javascript Adaption umgesetzt - OHNE - den original AVR Code in einem Javascript 
AVR Emulator zu verwenden.

```
Wir haben das ursprüngliche Projekt funktional in JavaScript nachgebildet, aber nicht den originalen AVR-Code ausgeführt.

Der Unterschied ist:
Unsere Umsetzung	                                          AVR-Emulator-Ansatz
Spielmechanik direkt in JavaScript programmiert	            Originaler AVR-Assembler- oder C-Code bleibt erhalten
Ballphysik wird durch JavaScript berechnet	                AVR-Code wird von einer virtuellen AVR-CPU ausgeführt
Poti, Tastatur und Spielablauf sind JavaScript-Funktionen	  Ein- und Ausgänge des AVR werden emuliert
Audioausgabe über Web Audio API	                            Emulierte AVR-Ausgänge werden in Audio-/XY-Signale umgesetzt

Das bedeutet: Unsere Version orientiert sich am Prinzip von Tennis for Two und erzeugt eine vergleichbare Funktionalität.
Sie ist aber keine originalgetreue Portierung der AVR-Implementierung.

Ein AVR-Emulator wäre ein anderer und durchaus interessanter Ansatz: Man könnte versuchen, den originalen AVR-Code unverändert
im Browser auszuführen und dessen Ausgänge auf die Stereo-Audioausgabe abzubilden.

Das wäre dann tatsächlich eine Emulation der ursprünglichen Hardware-Implementierung und nicht nur eine JavaScript-Neuimplementierung.
```
