# Stachelschwein Scanner

Das kleinste System, das noch Stachelschwein ist: ein Zuhörer auf dem Dach. Es muss nichts fliegen.

## Reihenfolge

1. **Remote ID.** EU Direct Remote Identification seit 1. Januar 2024 (C1 bis C3 in Open, jede Drohne in Specific). Norm EN 4709-002 / ASTM F3411. Handy-App für 0 EUR, ESP32-S3 für rund 12 EUR. OpenDroneID. Sieht keine C0-Mini, kein Glasfaser-FPV, keinen dunklen Anflug.
2. **Akustik.** Vier ICS-43434 in einer 91-mm-Kiste (VolAnti-Muster). Hört den Rotor-Kamm, auch ohne Funk. In der Größe kein Peiler, nur Empfindlichkeit.
3. **Funk.** RTL-SDR hört kein 2,4 GHz (R820T2 endet bei rund 1,8 GHz). Für OcuSync: HackRF / Lime / Blade, oder Aaronia AARTOS als deutsche Profiebene. DJI DroneID ist eine andere Familie als EU-RID (RUB, NDSS 2023).
4. **Bestätigung.** Pi Camera Module 3 nach oben. Nie der erste Detektor.

## Was kein Dachradar ist

- Infineon BGT60TR13C: deutscher 60-GHz-Chip, Datenblatt 15 m. Zimmer, nicht Stadt.
- HENSOLDT SPEXER 2000 3D MkIII: deutsches C-UAS-Radar, Ebene zwei (Feuerwehr, THW, Bundeswehr).

## Wochenend-Stückliste

| Kiste | Inhalt | EUR, Schätzung |
|---|---|---|
| Handy | OpenDroneID / Drone Scanner | 0 |
| RID | ESP32-S3, Kabel, Gehäuse | 25 |
| Akustik | 4 Mikrofone, ESP32, Druckgehäuse | 50 |
| Gehirn | Raspberry Pi 5 (Cambridge / Pencoed, Wales) | 110 |

Die Fläche: https://wunderglobe.com/stachelschwein/scanner
