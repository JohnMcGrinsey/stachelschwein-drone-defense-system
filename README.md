# Stachelschwein DDS

**Das dezentrale Drohnenschild für Deutschland.** Offenes System, günstige Sensoren, günstige
Abfangdrohnen, ein gemeinsames Protokoll.

Jedes geeignete Haus bekommt einen Sensor auf dem Dach. Jedes geeignete Haus bekommt eine
Abwehrdrohne mit sprengstofffreien Fangmitteln, zum Beispiel Netzen. Alle Knoten laufen auf einer
gemeinsamen Plattform. Fünf Millionen Sensoren und Abfangdrohnen schützen zusammen den deutschen
Luftraum.

Darüber legt Stachelschwein die nächste Schicht: Feuerwehr und Technisches Hilfswerk erhalten
weiterreichende Sensoren und leistungsfähigere Abfangsysteme. Das System ist von Anfang an modular
und so gebaut, dass es später in die Informations- und Führungsstruktur von Bundeswehr und NATO
eingesteckt werden kann.

## Warum

Angriffswellen mit zehntausend Drohnen sind keine Theorie mehr. Dagegen hilft keine einzelne teure
Rakete. Dagegen hilft Masse, die man in Wochen statt in Legislaturperioden ausrollen kann.

Bottom-up. Schnell. Billig. Fläche statt nur Flughafen.

## Was hier entsteht

Dieses Repository ist der Software- und Protokollteil. Zentral und gemeinsam entwickelt wird nur
das Standardisierte:

| Ordner | Inhalt |
|---|---|
| `protocol/` | Das Nachrichtenformat: Detektion, Fusion, Auftragsvergabe, Quittung |
| `hardware/` | Steckbriefe möglicher Sensoren und Abfangdrohnen, Plug-and-play-Adapter |
| `docs/` | Systementwurf, Betriebsfragen, offene Punkte |

Die Plattform ist offen für Plug-and-play verschiedener Sensor- und Drohnensysteme. Wer eine Kamera,
ein Mikrofonarray, ein Radar oder eine Abfangdrohne mitbringt, schreibt einen Adapter gegen das
Protokoll und ist Teil des Netzes.

## Lesen

Die Projektfläche, auf der das System gebaut wird, steht unter
[wunderglobe.com/stachelschwein](https://wunderglobe.com/stachelschwein). Erstes benanntes Produkt:
**Stachelschwein DDS Scanner v0.1** (Stückliste, 3D-Unit, Zentrale). Deutsch unter `/stachelschwein/de`.

Dieses Repository ist der Spiegel: Protokoll, Hardware-Minima, Systementwurf, Teileliste. Apache-2.0.
Lesen darf jeder. Die Fläche zum Durchklicken ist die Website, nicht GitHub.

## Simulation

Im Wunderglobe läuft eine Simulation des Frankfurt-Szenarios: Sensoren auf den Dächern, eine
Angriffswelle auf Knopfdruck, Triangulation, Startfreigabe, zehn koordinierte Abfangdrohnen pro
Angreifer.

- Projektfläche: [wunderglobe.com/stachelschwein](https://wunderglobe.com/stachelschwein)
- Simulation: [wunderglobe.com/play](https://wunderglobe.com/play), PLAY GAMES, SIM STACHELSCHWEIN
- Argument im Magazin: [wunderglobe.com/mag/projekt-stachelschwein](https://wunderglobe.com/mag/projekt-stachelschwein)
- McGrinsey-Magazin: [mcgrinsey.com/magazin/projekt-stachelschwein](https://mcgrinsey.com/magazin/projekt-stachelschwein/)

Stachelschwein ist ein Unterprojekt von Wunderglobe. Hier liegt der offene Code.

## Haltung

Wir sind Bürger, die eine resiliente Luftverteidigungs-Infrastruktur für notwendig halten, und
deshalb mit dem Aufbau beginnen. Reine Verteidigung. Kein Verkauf von Waffensystemen. Im Rahmen der
Gesetze.

- Wir installieren ab sofort.
- Wir schalten erst nach Abstimmung mit den Behörden scharf.
- Wir erzeugen Einsatzbereitschaft. Den Startknopf drückt im Ernstfall, wer dazu befugt ist.

So entsteht die Fläche, bevor die Regularien fertig sind. Die Zuständigkeiten können parallel
wachsen.

## Mitmachen

Lesen darf jeder. Schreibrechte liegen bei John McGrinsey. Wer mitbauen will, ist willkommen: mach
ein Issue auf oder schick einen Pull Request. Schnelle Koordination durch staatliche Stellen ist
ausdrücklich erwünscht.

## Lizenz

Apache License 2.0, siehe [LICENSE](LICENSE). Permissiv, mit ausdrücklicher Patentlizenz, damit ein
Hersteller einen Adapter bauen kann, ohne später ein Patentproblem zu erben. Die Wahl ist nicht in
Stein gemeißelt: wenn ein besserer Rahmen für ein Verteidigungsprotokoll auftaucht, reden wir darüber.
