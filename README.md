Ein einfaches Script um den Robby per HTTP-Request zu steuern.

Natürlich müssen die Einstellungen entsprechend angepasst werden:

- Benutzername und Passwort sind die vom Robonect-Modul.
- Robby-IP ist natürlich die IP-Addresse vom Robonect-Modul. (muss statisch vergeben sein!)
- Dauer ist die Mähdauer in Minuten.
- Ansonsten sind für die Funktion keine weiteren Einstellungen nötig.

Um den Robby loszuschicken wird einfach der Wert vom Datenpunkt geändert.
In meinem Fall sind das:
- 0 für Normal
- 1 für Ab Ladestation
- 2 für Außen
- 3 für Innen
- 4 für Home

<img src="Robonect-Blockly.png">
