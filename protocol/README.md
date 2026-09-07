# Das Protokoll

Ein Knoten ist ein Sensor, eine Abfangdrohne oder beides auf einem Dach. Das Protokoll ist das
Einzige, was alle Knoten teilen müssen. Alles andere darf sich unterscheiden: Hersteller, Sensorart,
Rechenleistung, Netzanbindung.

Vier Nachrichten tragen den ganzen Ablauf.

| Nachricht | Von | An | Zweck |
|---|---|---|---|
| `DETECTION` | Sensorknoten | Leitsystem | Ich habe etwas gehört oder gesehen, hier ist meine Peilung |
| `TRACK` | Leitsystem | alle Knoten in der Zelle | Aus mehreren Detektionen wurde eine Spur, hier ist sie |
| `TASKING` | Leitsystem | ausgewählte Abfangknoten | Startfreigabe, Ziel, Rolle im Verbund |
| `OUTCOME` | Abfangknoten | Leitsystem | Was passiert ist: gefangen, verfehlt, abgebrochen |

## Grundsätze

- **Ein Knoten meldet nur, was er gemessen hat.** Peilung, Zeit, Güte. Nie eine fertige Position:
  die entsteht erst aus mehreren Meldungen.
- **Die Fusion ist zentral, die Ausführung ist verteilt.** Das Leitsystem rechnet die Spur, die
  Knoten fliegen. Fällt das Leitsystem aus, fallen nicht die Knoten aus.
- **Redundanz ist Absicht.** Auf einen Angreifer werden mehrere Abfangdrohnen angesetzt, weil eine
  einzelne scheitern darf.
- **Jede Nachricht ist signiert.** Ein Knoten, dem niemand vertraut, ist ein Knoten, den jeder
  ignoriert.
- **Scharfschalten ist nie eine Nachricht dieses Protokolls.** Das System erzeugt
  Einsatzbereitschaft. Die Freigabe kommt von der Stelle, die dazu befugt ist.

## Stand

Entwurf. Die Feldnamen und die Kodierung stehen noch nicht fest. Was steht, ist die Aufteilung in
diese vier Nachrichten, und dass sie das Minimum sind.

Die Simulation im Wunderglobe fährt genau diesen Ablauf ab, damit man ihn ansehen kann, bevor
Hardware existiert: [wunderglobe.com/mag/projekt-stachelschwein](https://wunderglobe.com/mag/projekt-stachelschwein)
