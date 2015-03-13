naza-led
========

Homepage des Projektes ist http://tinue.github.io/naza-led

Der Simulator ist hier beschrieben: http://blog.erzberger.ch/multikopter-led-simulator

Versionsnachweis:

- 13. M�rz 2015
 - NazaLED kompiliert (und l�uft) nun f�r ATtiny85, und auch wieder f�r ATmega328
- 1. M�rz 2015
 - NazaLEDSimulator eingecheckt.
 - Keine �nderungen beim NazaLED
- 10. Februar 2015
 - Umgestellt auf ATtiny85 als Mikroprozessor. Arduino Pro Mini l�uft nicht mehr ohne �nderungen.
 - Abfrage der Fernsteuerung via Interrupt, anstelle von Polling (pulseIn). Die Naza LED wird so auch
  bei schnellen Abfolgen (rasches gr�nes Blinken, Rot blinken bei Akku leer) sauber nachgezeichnet.
 - Einige Fehler behoben (z.B. waren ron und gr�n Input vertauscht).
- 11. April 2014
 - �nderungen von Pascal eingepflegt (vor allem Flugmodus mit Naza)
 - Weitere Farbmodi (Regenbogen, basierend auf den Adafruit "Strandtest" Beispielen)
- 19. M�rz 2014
 - Fehler bei 4 Motoren behoben
- 18. M�rz 2014
 - Extra-Ring funktioniert jetzt im Polizei-Modus
 - Rot/Gr�n war vertauscht beim Naza Licht
- 17. M�rz 2014
 - DISCLAIMER: Einige Funktionen sind nicht getestet (Extra-Ring im Polizeilicht-Modus; Schalter f�r Helligkeit)
   Test wird folgen, sobald die Hardware (Patch-Kabel) eingetroffen sind.
 - Neu: Polizeilicht-Modus
 - Neu: Helligkeit via Dreiwegschalter; Poti wird nur noch f�r Lichtmodus gebraucht. Davon kann man jetzt 16 statt 4 einstellen.
 - Code-Cleanup v.a. bei Unterst�tzung f�r unterschiedliche Motorenzahl.
- 9. M�rz 2014 2014
 - Fehler beseitigt: readNazaColorIndex wurde zu h�ufig aufgerufen, so dass sich der Wert zur Unzeit �ndern konnte
 - Neu: Drei Helligkeitsstufen, statt stufenlos. Vorteil: Poti muss f�r volle Helligkeit nicht mehr m�glichst knapp
        an den n�chsten Lichtmodus herangedreht werden. Es reicht, zum n�chsten Modus und dann etwas zur�ck zu drehen,
        was schneller geht.
 - Neu: Flugmodus sieht jetzt aus wie ein Flugzeug: Vorne rechts rot, vorne links gr�s und hinten weiss (funktioniert
        nur bei Hexakopter).
 - Allgemein: Code bereinigt, lesbarer und robuster gemacht.
- Januar 2014: Erste Version
