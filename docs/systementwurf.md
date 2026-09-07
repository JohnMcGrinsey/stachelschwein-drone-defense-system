# Systementwurf

Stand: 7. September 2026. Erster Wurf, bewusst grob.

## Die drei Ebenen

1. **Der Knoten.** Ein Dach, ein Sensor, optional eine Abfangdrohne. Billig, viele, austauschbar.
2. **Das Leitsystem.** Nimmt Detektionen entgegen, macht daraus Spuren, vergibt Abfangaufträge.
   Läuft pro Zelle, nicht pro Land.
3. **Die zweite Schicht.** Feuerwehr und Technisches Hilfswerk mit weiterreichenden Sensoren und
   leistungsfähigeren Abfangsystemen. Sie hängt am selben Protokoll.

## Der Ablauf, den die Simulation zeigt

1. Mehrere Sensorknoten hören dasselbe Geraeusch und melden ihre Peilung.
2. Das Leitsystem trianguliert daraus eine Spur.
3. Es gibt die Startfreigabe für zehn koordinierte Abfangdrohnen, damit eine Redundanz da ist,
   falls eine scheitert.
4. Die Abfangdrohnen nehmen den Angreifer in die Zange und fangen ihn mit einem Netz.
5. Der Fang wird quittiert. Der Angreifer trifft sein Ziel nicht.

## Offene Punkte

- Was nach dem Fang passiert. Wegtragen ist besser als fallen lassen, und braucht Traglast.
- Zeitsynchronisation über fünf Millionen Knoten, ohne dass jeder ein GPS braucht.
- Falschalarme. Ein Netz über einer Amsel ist ein teurer Fehler.
- Rechtsrahmen für den Betrieb im Ruhezustand, getrennt von der Scharfschaltung.
- Die Zellgröße: wie viele Knoten hängen an einem Leitsystem, bevor es geteilt wird.
