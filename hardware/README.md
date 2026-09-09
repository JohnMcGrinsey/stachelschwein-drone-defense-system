# Hardware

Das Projekt baut vorerst keine Hardware. Es beschreibt, was ein Knoten können muss, damit
vorhandene Hardware angeschlossen werden kann.

## Sensorknoten, Mindestanforderung

- Richtungsschätzung für ein akustisches oder optisches Ereignis, mit einer Güteangabe
- Zeitstempel, der über die Knoten hinweg vergleichbar ist
- Netzanbindung, die eine kurze Nachricht in unter einer Sekunde loswird
- Stromversorgung, die einen Ausfall des Hausnetzes übersteht

Ein Mikrofonarray auf einem Dach erfüllt das. Eine Kamera mit Bewegungserkennung auch. Ein Radar ist
besser und teurer, und gehört auf die zweite Schicht.

## Abfangknoten, Mindestanforderung

- Startbereit ohne menschliche Hand am Gerät
- Sprengstofffreies Fangmittel, zum Beispiel ein Netz
- Genug Reichweite und Steigrate, um ein Ziel im eigenen Zellradius zu erreichen
- Eine Rückmeldung, ob der Fang gelungen ist

## Adapter

Ein Adapter übersetzt zwischen einem konkreten Gerät und dem Protokoll. Er gehört in dieses
Repository, damit ein zweiter Betreiber dasselbe Gerät ohne Rückfrage anschließen kann.

## Erste Ernte

`parts.json` ist der wilde Katalog (Scanner, Gehirn, Funk, Akustik, Radar, Abfang, Testziele),
noch ungerankt. Lesbar unter [wunderglobe.com/stachelschwein/parts](https://wunderglobe.com/stachelschwein/parts).
