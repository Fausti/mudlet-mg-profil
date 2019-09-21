# mudlet-mg-profil
Mein Mudletprofil für das deutsche MUD Morgengrauen.

![Screenshot 2019-09-21 01 15 31](https://user-images.githubusercontent.com/229010/65372440-9c67b180-dc70-11e9-83b0-13d42f7f4c8a.png)

## Installation
- Verzeichnis anlegen (z.B.: "D:\\Morgengrauen")
- Inhalt des Repos dort rein
- In Mudlet den Skripteditor starten
- alle XML Dateien importieren
- unter *Skripte/Morgengrauen UI* rechts den Pfad zum angelegten Verzeichnis anpassen
- Profil speichern und Mudlet neu starten

## Automapper
- #MAP listet ein paar nützliche Befehle auf

- #ROOM SYMBOL "A" zum Setzen eines Kürzels für den aktuellen Raum, maximal 3 Zeichen lang
- #AREA SET "..." zum Setzen des Gebietes in dem sich der aktuelle Raum befindet
- Mittels *Rechtsklick* auf einen Raum auf der Karte wird zwischen Raum/Weg Grafik gewechselt

## Anmerkungen

- [**BUG**] Raumausgänge werden erst ab der zweiten empfangenen Raumbeschreibung eingefärbt

- [**TODO**] Karten werden zwar automatisch beim Start von Mudlet geladen, aber nicht automatisch gespeichert. **Bitte vor dem Ausloggen / Beenden von Mudlet mittels "#map save" von Hand erledigen!**

- [**BUG**] Manchmal reagiert der Rechtsklick auf Räume nicht korrekt. Mal wird der falsche Raum geändert, mal passiert gar nix...

- [**FEATURE**] Die Raumausgänge sind nicht nur farbig hervorgehoben, sondern lassen sich auch anklicken um eine Bewegung in die passende Richtung auszuführen. Nett falls man mal wieder nicht an die Tastatur kommt weil das Katerchen auf dem Schoß liegt ;)

- [**FEATURE**] Die farbigen Ebenenmeldungen lassen sich auch anklicken um direkt in die richtige Ebene antworten zu können.
