# CLUEDO :detective:
## Ein Modellierungsprojekt für Software Engineering WI22A3/S3
##### Gruppenmitglieder:
###### Katharina Bäuml, Jan Hoang, Anton Mundschau

# Inhaltsverzeichnis
- [Was ist Cluedo?](#was-ist-cluedo)
	- [Die Charaktere](#die-charaktere)
		- [Fräulein Gloria](#fräulein-gloria-die-verführerin)
		- [Baronin von Porz](#baronin-von-porz-die-partybiene)
		- [Professor Bloom](#professor-bloom-der-intellektuelle)
		- [Oberst von Gatow](#oberst-von-gatow-das-alphatier)
		- [Reverend Grün](#reverend-grün-der-womanizer)
		- [Dr. Orchidee](#dr-orchidee-das-genie)
	- [Wie wird gespielt?](#wie-wird-gespielt?)
- [Anwendungsanalyse](#use-case-beschreibungen)
	- [Use Case Beschreibung 1](#use-case-1)
	- [Use Case Beschreibung 2](#use-case-2)
	- [Use Case Beschreibung 3](#use-case-3)
- [Klassenmodell](#klassenmodell)
	- [Klassendiagramm](#klassendiagramm)
	- [Data Dictionary](#data-dictionary)
- [Sequenzdiagramm](#sequenzdiagramm)


# Was ist CLUEDO?

> **Die Einladungen wurden überbracht.  
Die Gäste trafen ein.  
Der Gastgeber wurde ermordet. Kaltblütig umgebracht.  
Ging es um sein Geld ...?**  

Sein Onkel, Professor Schwarz, hätte gewusst, wer dahintersteckt, doch leider ist auch er schon seit Jahren tot. Die sechs geheimnisvollen Gäste stehen nun unter Mordverdacht, und es liegt an dir, das Rätsel zu lösen.

## Die Charaktere

### Fräulein Gloria, die Verführerin
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Gloria.png)

*Schön und begehrenswert. Aber auch skrupellos und manipulierend?*  
Gloria war schon immer eine schöne Frau, aber leider sehr kaltherzig. Dr. Schwarz und sie wuchsen zusammen auf und gingen gemeinsam durch dick und dünn, doch je älter sie wurden, desto angespannter wurde ihre Beziehung. Schwarz warf Gloria vor, seinen Onkel bei Investitionen falsch beraten zu haben, doch nachdem sie seine Einladung in die Villa Neubrunn erhielt, dachte Gloria, alles sei vergeben und vergessen ...  

------------

### Baronin von Porz, die Partybiene
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Porz.png)

*Kokettierend und verschwiegen. Doch auch habgierig und doppelzüngig?*  
Ihr wahres Alter ist nur eines von vielen Geheimnissen der selbsternannten Baronin, die sich vom Kleinstadtmädchen zur Salonlöwin entwickelt hat. Von ihren drei Ehemännern weiß man nur, dass sie alle sehr plötzlich gestorben sind, und Professor Schwarz hat das Zeitliche gesegnet, bevor er Gatte Nr. 4 werden konnte. Es ist unklar, ob sie in der Villa Neubrunn nun einen neuen Mann sucht oder ein Mordopfer ...  

------------

### Professor Bloom, der Intellektuelle
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Bloom.png)

*Furchtlos und exzentrisch. Dabei auch zwanghaft und paranoid?*  
Mutig sucht er nach verschütteten Gräbern, antiken Statuen und versunkenen Städten: Professor Bloom ist ein besonders benteuerlustiger Archäologe. Professor Schwarz finanzierte seine Expeditionen, bis sie sich plötzlich im Streit trennten. Ohne Ausgrabung in Sicht langweilte sich Bloom entsetzlich, und da war Dr. Schwarz’ Einladung ein willkommener Silberstreif am Horizont. Professor Bloom traf übrigens als Erster in der Villa ein ...  

------------

### Oberst von Gatow, das Alphatier
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Gatow.png)

*Patriot und Menschenfreund. Zugleich auch ein Lügner und Egoist?*  
In der Öffentlichkeit gilt er als Held: Oberst von Gatow ist ein hochdekorierter, erfolgreicher und beliebter Offizier. Hinter seinen Ehrenmedaillen schwelen jedoch Gerüchte über Schwarzmarktgeschäfte und Hochverrat – Gerüchte, für die er lange Zeit jemanden bezahlte, damit sie geheim blieben. Nun glaubt Gatow, Dr. Schwarz wolle ihn erpressen, weshalb es ihm unter den Nägeln rennt, die Villa Neubrunn nach Beweisen zu durchsuchen ...  

------------

### Reverend Grün, der Womanizer
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Gruen.png)

*Geistreich und charmant. Aber auch nachtragend und dekadent?*  
Der Hochstapler Grün gab sich bereits als Prinz, Pilot, Arzt und Rechtsanwalt aus, doch nach jahrelangen Betrügereien geriet er in Schwierigkeiten, weshalb er vorübergehend in Deckung ging, und zwar als Reverend. Grün glaubt, nur Professor Schwarz kannte seine wahre Identität, weshalb ihn die Einladung seines Neffen in höchste Alarmbereitschaft versetzte. Fest entschlossen, sein Geheimnis zu wahren, trifft er nervös in der Villa ein ...  

------------

### Dr. Orchidee, das Genie
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/Sonstiges/Orchidee.png)

*Geheimnisvoll und abenteuerlich. Zugleich auch ehrgeizig und kriminell?*  
Orchidee wurde als Teenager von Dr. Schwarz adoptiert und in einem Schweizer Internat untergebracht, bis man sie wegen eines Vergiftungsvorfalls hinauswarf. Danach wurde Frau Weiß ihre Hauslehrerin, und Orchidee entschied sich für eine Karriere als Biologin. Bei ihren Forschungen über giftige Pflanzen stieß sie auf ein medizinisch hochwirksames Gewächs, doch diese Entdeckung wollte sie mit niemandem teilen – nur mit ihrem Adoptivvater ...  


## Wie wird gespielt?
Löse den Mordfall! Wer war's? Mit welcher Waffe? In welchem Raum?
- Erstelle mit deinen Freunden eine Spielrunde, indem ihr der Lobby mit dem gleichen Namen beitretet!
- Ziehe durch die Räume der Villa und spreche jeweils einen Verdacht aus, wer den Mord mit welcher Waffe in welchem Raum begangen haben könnte.
- Notiere deine Hinwesie. Durch das verdächtigen kannst du nach und nach die Personen, Waffen und Räume ausschließen.
- Wenn du die Lösung des Falls kennst, darfst du einmal Anklage erheben.
- Die Fallakte entscheidet, ob du recht hattest. Falls du daneben liegst, scheidest du aus dem Spiel aus, also musst du dir sicher sein!

*In Anlehnung am klassischen Cluedo ohne Beweiskarten: [Original Cluedo - Rules (1996 Version)](https://www.cluedofan.com/origrule.htm)*

# Anwendungsanalyse
## Use Case Beschreibung 1
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

## Use Case Beschreibung 2
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

## Use Case Beschreibung 3
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

# Klassenmodell
## Klassendiagramm

![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/PNG/Klassendiagramm.png)

## Data Dictionary

| Name | Beschreibung | Eigenschaften | Verwendung | Instanzen |
| ------------ | ------------ | ------------- | ---------- | --------- |
| Spieler | Ein Spieler ist ein Bestandteil des Spiels und ist zugleich die Spielfigur. Die Spieler sind nacheinander an der Reihe. Der Spieler bewegt sich durch die Villa über Gitterfelder, nachdem er gewürfelt hat. Ein Raum darf nur durch die Tür betreten werden, sobald man einen betritt, verfällt der Rest des Wurfes und man muss im Raum stehen bleiben. | name, person, amZug | Ein Spieler kann: sich bewegen, einen Verdacht aussprechen, würfeln, eine Anklage erheben, einen Hinweis notieren, seinen Zug beenden | 2..6 |
| Spielrunde | Eine Spielrunde ist ein kompletter Spielablauf bis 1 Spieler den Mörder gefunden hat oder alle Spieler ihre Anklage verbraucht haben. Eine Runde besteht aus mindestens 2 und maximal 6 Spielern | name | Durch eine Spielrunde kann: eine Spielrunde gestartet/beendet werden, der Zug eines Spielers automatisch beendet werden, das Zugrecht einem anderen Spieler zugeteilt werden, Karten an die Spieler und die Fallakte ausgeteilt werden, Hinweismeldungen angezeigt werden | 0..1 |
| Fallakte | Die Fallakte setzt sich aus 3 Karten zusammen (1 Personenkarte / 1 Waffenkarte / 1 Raumkarte), welche am Anfang von der Spielrunde vom System beim Karten austeilen ausgewählt werden und damit den gesuchten Mörder bestimmen | Besteht aus 3 Karten | - | 1 |
| Karte | 18 von den 21 Karten sind Eigentum der Spieler, welche gleichmäßig aufgeteilt werden. Die anderen 3 Karten werden in die Fallakte gelegt | Entweder in der Fallakte oder beim Spieler | Eine Karte befindet sich entweder bei einem Spieler oder in der Fallakte | 21 |
| Personenkarte | Eine Personenkarte ist eine von 6 Personen (Gloria, Porz, Bloom, Gaton, Grün, Orchidee), welche an die Spieler und die Fallakte verteilt werden | person | Greift auf <<enumeration>> Person zu, in der die 6 Personen aufgelistet sind | 1 |
| Raumkarte | Eine Raumkarte ist eine von 9 Räumen (Küche, Speisezimmer, Salon, Halle, Arbeitszimmer, Bibliothek, Billiardzimmer, Wintergarten, Musikzimmer), welche an die Spieler und die Fallakte verteilt werden | waffe | Greift auf <<enumeration>> Waffentyp zu, in der die 6 Waffen aufgelistet sind | 1 |
| Waffenkarte | Eine Waffenkarte ist eine von 6 Waffen (Seil, Dolch, Rohrzane, Pistole, Leuchter, Heizungsrohr), welche an die Spieler und die Fallakte verteilt werden | raum | Greift auf <<enumeration>> Raumtyp zu, in der die 9 Räume aufgelistet sind | 1 |
| Spielbrett | Das Spielbrett ist das Herz des Spiels, auf welchem sich die Spieler auf Gitterfeldern bewegen. Dadurch gelangen Sie in die Räume und Geheimgänge. Das Spielbrett stellt eine Villa dar mit dem Namen  "Villa Neubrunn" | Komposition aus: Gitterfeld, Geheimgang, Raum, Waffe | - | 1 |
| Waffe | Es existieren 6 Waffen pro Spielbrett | Waffe, Ort | - | 6 |
| Gitterfeld | Ein Spielbrett hat 193 Gitterfelder, auf dem sich ein Spieler bewegt und dadurch Räume und Geheimgänge betreten kann. | hatSpieler | - | 193 |
| Geheimgang | Es existieren 2 Geheimgänge pro Spielbrett, welche jeweils diagonal in den Eckröumen der Villa gegenüberliegen (Küche und Zimmer sowie Wintergarten und Salon). Wenn man am Anfang seines Zugs in einen dieser Räume steht, darf man anstatt zu würfeln und zu ziehen, den Geheimgang nutzen. | verbindung | - | 4 |
| Raumkarte | Es gibt 9 Räume, welche auf dem Spielbrett verteilt sind. In einem Raum dürfen beliebig viele Figuren stehen. Jedoch darf ein Spieler den Raum nicht betreten oder verlassen, wenn der Eingang von einem anderen Spieler blockiert wird | raum, hatSpieler | - | 9 |
| Würfel | Eine Spielrunde besitzt 2 Würfel. Pro Spielzug eines Spielers werden beide Würfel gewürfelt. Die gewürfelte Augenzahl kann genutzt werden, um die Spielfigur durch die Villa über die Gitterfelder zu bewegen. | augenzahl | - | 2 |
| Hinweiszettel | Jeweils ein Spieler hat einen Hinweiszettel. Auf dem Hinweiszettel notiert sich ein Spieler die gesammelten Hinweise. | notizen | - | 2..6 pro Spielrunde // 1 pro Spieler |
| Anklage | Ein Spieler kann bis zu 1 mal pro Spielrunde eine Anklage gegen einen anderen Spieler erheben, mit dem Ziel den Mörder zu finden. Ist die Anklage korrekt (alle 3 Karten des Mörders richtig genannt), gewinnt er das Spiel, ansonsten ist der Spieler "eliminiert" und kann sich nicht mehr aktiv am Spiel beteiligen, sondern nur noch auf einen Verdacht von anderen Spielern reagieren. | person, waffe, raum | Durch eine Anklage kann: eine runde beendet werden, ein Spieler eliminiert werden | 0..6 pro Spielrunde // 0..1 pro Spieler |
| Verdacht | Ein Spieler kann über den Verlauf einer Spielrunde mehrere Verdachte aussprechen. Durch einen Verdacht hat der Spieler die Möglichkeit, herauszufinden, wer den Mord womit und wo begangen hat. Die anderen Spieler zeigen dem Spieler die verdächtigen Karte, welche man auf seinem Hinweiszettel notiert und somit Stück für Stück die falschen Personen/Waffen/Räume ausschließt. | person, waffe, raum | - | 0..* |

# Sequenzdiagramm
![](https://github.com/dhbw-jhoang/dhbw_software_engineering_spiel/blob/main/PNG/Sequenzdiagramm.png)