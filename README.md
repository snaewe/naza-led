naza-led
========

Homepage des Projektes ist http://tinue.github.io/naza-led

Versionsnachweis:
- 18. M�rz
 - Extra-Ring funktioniert jetzt im Polizei-Modus
 - Rot/Gr�n war vertauscht beim Naza Licht
- 17. M�rz
 - DISCLAIMER: Einige Funktionen sind nicht getestet (Extra-Ring im Polizeilicht-Modus; Schalter f�r Helligkeit)
   Test wird folgen, sobald die Hardware (Patch-Kabel) eingetroffen sind.
 - Neu: Polizeilicht-Modus
 - Neu: Helligkeit via Dreiwegschalter; Poti wird nur noch f�r Lichtmodus gebraucht. Davon kann man jetzt 16 statt 4 einstellen.
 - Code-Cleanup v.a. bei Unterst�tzung f�r unterschiedliche Motorenzahl.
- 9. M�rz 2014
 - Fehler beseitigt: readNazaColorIndex wurde zu h�ufig aufgerufen, so dass sich der Wert zur Unzeit �ndern konnte
 - Neu: Drei Helligkeitsstufen, statt stufenlos. Vorteil: Poti muss f�r volle Helligkeit nicht mehr m�glichst knapp
        an den n�chsten Lichtmodus herangedreht werden. Es reicht, zum n�chsten Modus und dann etwas zur�ck zu drehen,
        was schneller geht.
 - Neu: Flugmodus sieht jetzt aus wie ein Flugzeug: Vorne rechts rot, vorne links gr�s und hinten weiss (funktioniert
        nur bei Hexakopter).
 - Allgemein: Code bereinigt, lesbarer und robuster gemacht.

- Januar 2014: Erste Version
