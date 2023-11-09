| Geschäftsprozess  |  Spielzug machen  |
| :------------ | :------------ |
|  **Ziel, Ergebnisse**  |  Spielzug des Spielers ist beendet  |
|  **Akteure**  |  Spieler |
|  **Vorbedingungen**  |  Spiel wurde gestaret,<br>Spieler ist eingeloggt,<br>Spieler nimmt am Spiel teil,<br>Spieler ist am Zug  |
|  **Auslösendes Ereignis**  |  Spieler ist am Zug  |
|  **Nachbedingung bei Erfolg**  |  Nächster Spieler ist am Zug  |
|  **Nachbedingung bei Fehlschlag**  |  Spieler ist immer noch am Zug  |
|  **Eingehende Daten**  |  Spieler der am Zug ist  |
|  **Ausgehende Daten**  |  Würfelzahl,<br>Spieler-Position,<br>Verdacht (optional)  |
|  **Ablauf**  |   1) Spieler würfelt<br>2) Spielfigur bewegen<br>3) Verdacht aussprechen  |
|  **Erweiterung**  |  2a) Geheimgang benutzen<br>3a) Anklage machen  |
|  **Alternativen**  |  2a) Im Raum stehen bleiben<br>3a) Verdacht nicht aussprechen  |

| Geschäftsprozess  |  Anklage machen  |
| :------------ | :------------ |
|  **Ziel, Ergebnisse**  |  Spiel gewinnen,<br>Spiel verlieren|
|  **Akteure**  |  Spieler  |
|  **Vorbedingungen**  |  Spiel wurde gestartet,<br>Spieler ist eingeloggt,<br>Spieler ist am Zug  |
|  **Auslösendes Ereignis**  |  Spieler ist am Zug  |
|  **Nachbedingung bei Erfolg**  |  Spiel ist beendet  |
|  **Nachbedingung bei Fehlschlag**  |  Spieler hat verloren  |
|  **Eingehende Daten**  |  -  |
|  **Ausgehende Daten**  |  Anklage (Raum, Person, Waffe) |
|  **Ablauf**  |  1) Anklage aussprechen<br>2) Fallakte einsehen  |
|  **Erweiterung**  |  -  |
|  **Alternativen**  |  -  |

| Geschäftsprozess  |  Hinweis notieren  |
| :------------ | :------------ |
|  **Ziel, Ergebnisse**  |  Hinweis notiert  |
|  **Akteure**  |  Spieler |
|  **Vorbedingungen**  |  Spiel wurde gestaret,<br>Spieler ist eingeloggt,<br>Spieler nimmt am Spiel teil  |
|  **Auslösendes Ereignis**  |  Spielzug wurde durchgeführt  |
|  **Nachbedingung bei Erfolg**  |  Neuer Hinweis wurde notiert  |
|  **Nachbedingung bei Fehlschlag**  |  Kein Hinweis wurde notiert  |
|  **Eingehende Daten**  |  Person, Waffe, Raum  |
|  **Ausgehende Daten**  |  -  |
|  **Ablauf**  |   1) Hinweis notieren  |
|  **Erweiterung**  |  1a) Person notieren<br>1b) Waffe notieren<br>1c) Raum notieren  |
|  **Alternativen**  |  1) Keinen Hinweis erhalten  |
