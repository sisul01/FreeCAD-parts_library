# FreeCAD-partlib
Contains various FreeCAD projects 

allgemeines:
------------
Was gehört rein:
alles was in grösseren Mengen eingekauft werden kann und benötigen mehr als 10 kontrukteure weltweit das teil?
besonders häufig genutzt werden und daher oft genormt sind und zugekauft werden können

nur englisch
nur metrisch
FeeCAD 0.18, frühere Versionen bitte konvertieren.

möglicht in Partdesign, dann Part, dann Draw

Konstruktionen möglichst einfach halten, es kommt dur auf Aussehen, Aussendimensionen und Masse für Verbindungsstellen an.
 
dateiname grosschrift, libpart in kleinschrift (pingelig,  aber im Sinne der Einheitlichkeit nötige Regelung)
Nur parametrisch veränderbar, kein phyton-script

organisation
-------------
Speichern mit thumbnail aber ohne Programmlogo, damit man in der Vorschau auch alles sieht

Nur .FCStd dateien speichern, andere Formate sind nicht erwünscht, das ist eine FC-Bibliothek, und Grösse möglichst klein halten.

Trennung von Quelldateien (_src Verzeichnis) und Bibliothektseintrag

Teile aus anderen Bibliotheken sind ins FC -Format zu überführen und als einfaches Bauteil zu speichern. Herkunft (webseite, Firma o.ä.) muss in den Project-Information hinterlegt werden. 
Bezugsquelle des Teils oder Hersteller sollte in den Projektinfos der Quelldateien, oder wenn nicht vorhanden, in den Bibliothelsdateien genannt werden.

Möglichst generische Quelldateien, die benötigten sonderlängen können dann daraus erzeugt werden.

Variable Masse dann in eine Tabelle mit aussagekräftigem Namen

README datei wenn bei den Quellen etwas besonders ist


lizenz
-------
Autor und Lizenz Project-Information hinterlegen


License
-------
[![Creative Commons License BY-NC-SA 3.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png "Creative Commons License")](http://creativecommons.org/licenses/by-sa/4.0/)
All files included in this repository are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)