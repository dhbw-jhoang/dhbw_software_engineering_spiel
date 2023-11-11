# CLUEDO :detective:
## Ein Modellierungsprojekt für Software Engineering WI22A3/S3
##### Gruppenmitglieder:
###### Katharina Bäuml, Jan Hoang, Anton Mundschau
------------
**Table of Contents**

[TOCM]

[TOC]

#H1 header
------------

## Was ist CLUEDO?

> **Die Einladungen wurden überbracht.  
Die Gäste trafen ein.  
Der Gastgeber wurde ermordet. Kaltblütig umgebracht.  
Ging es um sein Geld ...?**  

Sein Onkel, Professor Schwarz, hätte gewusst, wer dahintersteckt, doch leider ist auch er schon seit Jahren tot. Die sechs geheimnisvollen Gäste stehen nun unter Mordverdacht, und es liegt an dir, das Rätsel zu lösen.

### Die Charaktere

**Fräulein Gloria, die Verführerin**  
*Schön und begehrenswert. Aber auch skrupellos und manipulierend?*  
Gloria war schon immer eine schöne Frau, aber leider sehr kaltherzig. Dr. Schwarz und sie wuchsen zusammen auf und gingen gemeinsam durch dick und dünn, doch je älter sie wurden, desto angespannter wurde ihre Beziehung. Schwarz warf Gloria vor, seinen Onkel bei Investitionen falsch beraten zu haben, doch nachdem sie seine Einladung in die Villa Neubrunn erhielt, dachte Gloria, alles sei vergeben und vergessen ...  

**Baronin von Porz, die Partybiene**  
*Kokettierend und verschwiegen. Doch auch habgierig und doppelzüngig?*  
Ihr wahres Alter ist nur eines von vielen Geheimnissen der selbsternannten Baronin, die sich vom Kleinstadtmädchen zur Salonlöwin entwickelt hat. Von ihren drei Ehemännern weiß man nur, dass sie alle sehr plötzlich gestorben sind, und Professor Schwarz hat das Zeitliche gesegnet, bevor er Gatte Nr. 4 werden konnte. Es ist unklar, ob sie in der Villa Neubrunn nun einen neuen Mann sucht oder ein Mordopfer ...  

**Professor Bloom, der Intellektuelle**  
*Furchtlos und exzentrisch. Dabei auch zwanghaft und paranoid?*  
Mutig sucht er nach verschütteten Gräbern, antiken Statuen und versunkenen Städten: Professor Bloom ist ein besonders benteuerlustiger Archäologe. Professor Schwarz finanzierte seine Expeditionen, bis sie sich plötzlich im Streit trennten. Ohne Ausgrabung in Sicht langweilte sich Bloom entsetzlich, und da war Dr. Schwarz’ Einladung ein willkommener Silberstreif am Horizont. Professor Bloom traf übrigens als Erster in der Villa ein ...  

**Oberst von Gaton, das Alphatier**  
*Patriot und Menschenfreund. Zugleich auch ein Lügner und Egoist?*  
In der Öffentlichkeit gilt er als Held: Oberst von Gatow ist ein hochdekorierter, erfolgreicher und beliebter Offizier. Hinter seinen Ehrenmedaillen schwelen jedoch Gerüchte über Schwarzmarktgeschäfte und Hochverrat – Gerüchte, für die er lange Zeit jemanden bezahlte, damit sie geheim blieben. Nun glaubt Gatow, Dr. Schwarz wolle ihn erpressen, weshalb es ihm unter den Nägeln rennt, die Villa Neubrunn nach Beweisen zu durchsuchen ...  

**Reverend Grün, der Womanizer**  
*Geistreich und charmant. Aber auch nachtragend und dekadent?*  
Der Hochstapler Grün gab sich bereits als Prinz, Pilot, Arzt und Rechtsanwalt aus, doch nach jahrelangen Betrügereien geriet er in Schwierigkeiten, weshalb er vorübergehend in Deckung ging, und zwar als Reverend. Grün glaubt, nur Professor Schwarz kannte seine wahre Identität, weshalb ihn die Einladung seines Neffen in höchste Alarmbereitschaft versetzte. Fest entschlossen, sein Geheimnis zu wahren, trifft er nervös in der Villa ein ...  

**Dr. Orchidee, das Genie**  
*Geheimnisvoll udn abenteuerlich. Zugleich auch ehrgeizig und kriminell?*  
Orchidee wurde als Teenager von Dr. Schwarz adoptiert und in einem Schweizer Internat untergebracht, bis man sie wegen eines Vergiftungsvorfalls hinauswarf. Danach wurde Frau Weiß ihre Hauslehrerin, und Orchidee entschied sich für eine Karriere als Biologin. Bei ihren Forschungen über giftige Pflanzen stieß sie auf ein medizinisch hochwirksames Gewächs, doch diese Entdeckung wollte sie mit niemandem teilen – nur mit ihrem Adoptivvater ...  

### Wie wird gespielt?
Löse den Mordfall! Wer war's? Mit welcher Waffe? In welchem Raum?
- Erstelle mit deinen Freunden eine Spielrunde indem ihr der Lobby mit dem gleichen Namen beitretet!
- Ziehe durch die Räume der Villa und spreche jeweils einen Verdacht aus, wer den Mord mit welcher Waffe in welchem Raum begangen haben könnte.
- Notiere deine Hinwesie. Durch das verdächtigen kannst du nach und nach die Personen, Waffen und Räume ausschließen.
- Wenn du die Lösung des Falls kennst, darfst du einmal Anklage erheben.
- Die Fallakte entscheidet, ob du recht hattest. Falls du daneben liegst, scheidest du aus dem Spiel aus, also musst du dir sicher sein!

------------

## Use Case Beschreibungen
### Use Case 1
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

### Use Case 2
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

### Use Case 3
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

