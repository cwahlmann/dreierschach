# dreierschach V2.2

![Dreierschach Logo](/images/logo.svg "Dreierschach Logo")

Schach zu dritt - chess for three players - nah am Original auf 126 hexagonalen Feldern - nearly original on 126 hexagonal fields

Dreierschach © 2021 by Christian Wahlmann is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

- [Vollständige Spielregeln](#vollständige-spielregeln)
- [Kurzregeln](#kurzregeln)
- [Bauanleitung](#bauanleitung)

## Vollständige Spielregeln

Dreierschach ist eine Variation des klassischen Schachspiels für drei Spieler, mit dem Ziel, das klassische Setting und die offiziellen Regeln möglichst 1:1 zu übernehmen.

Dem oft bemängelten Problem von 2:1-Bündnissen wird durch eine veränderte Punkteverteilung begegnet. Es lohnt sich zu siegen, und weniger, zweiter zu sein.

Dies sind die überarbeiteten Spielregeln in Version 2.2.

Änderungen zur Vorversion:
- Das Spiel endet, sobald ein Spieler Schachmatt steht.
- Die Punkteverteilung (3, 1, 0) belohnt das Matt-Setzen.
- Umgewandelt wird wieder nach den original Schach-Regeln
    
### Spielmaterial

- ein Spielbrett mit 126 sechseckigen Feldern in drei Farben 
- 51 Spielfiguren, davon je 17 in einer Farbe: 

1x ![1 König](/images/white_king.svg "1 König") 
1x ![1 Dame](/images/white_queen.svg "1 Dame")
2x ![2 Türme](/images/white_rook.svg "2 Türme")
2x ![2 Springer](/images/white_knight.svg "2 Springer")
2x ![2 Läufer](/images/white_bishop.svg "2 Läufer")
9x ![9 Bauern](/images/white_pawn.svg "9 Bauern")

### Spielvorbereitung

Es wird ausgelost, welcher Spieler welche Farbe spielt. Dann werden die Figuren wie in der Abbildung auf das Spielbrett gestellt.

![Aufstellung](/images/board_setup.svg "Aufstellung")

Von der Grundlinie des jeweiligen Spielers aus stehen die Türme außen, daneben Läufer und Springer (wobei das Springer immer rechts steht), und in der Mitte König und Dame (diese steht immer rechts vom König auf einem Feld ihrer eigenen Farbe). Vor diesen Figuren stehen die 9 Bauern in einer Reihe.

### Spielstart

Ziel des Spiels ist es, den König eines Gegners Schachmatt zu setzen. Die Farben werden zu Beginn des Spieles ausgelost. Der Spieler mit der Farbe Weiß beginnt.

### Spielverlauf

Die Spieler ziehen der Reihe nach eine ihrer Figuren. Die Reihenfolge ist Weiß, Braun, Schwarz und so weiter.

Beim Ziehen werden zwei grundsätzliche Richtungen unterschieden:

**gerade**, d.h. entlang benachbarter Felder:

![gerade ziehen](/images/move_straight.svg "gerade ziehen")

**diagonal**, d.h. entlang gleichfarbiger Felder:

![diagonal ziehen](/images/move_diagonal.svg "diagonal ziehen")

Um diagonal zwischen zwei Feldern hindurchziehen zu können, muss eines davon frei sein. 

Eine Figur darf - mit Ausnahme des Springers - nur über freie Felder gezogen werden. Ist das Zielfeld von einer gegnerischen Figur besetzt, so wird diese geschlagen, d.h. vom Brett genommen und durch die eigene ersetzt. 
      
Die **Dame** darf gerade und diagonal beliebig weit ziehen:

![Dame ziehen](/images/move_queen.svg "Dame ziehen")

Der **König** darf wie die Dame ziehen, aber nur ein Feld weit:

![König ziehen](/images/move_king.svg "König ziehen")

Ein besonderer Zug ist die sogenannte **Rochade**: der König zieht an einen der Türme heran, der Turm setzt dann über ihn hinweg:

![Rochade](/images/move_rochade.svg "Rochade")

Dabei gilt:
- Alle Felder zwischen König und Turm müssen frei sein. 
- Weder König noch eines der Felder zwischen Turm und König dürfen durch eine gegnerische Figur bedroht sein. 
- Weder Turm noch König dürfen schon einmal bewegt worden sein. 
- Man unterscheidet zwischen kleiner Rochade (über 2 freie Felder) und großer Rochade (über 3 freie Felder). 

Wird der König eines Spielers bedroht, so ist er im **Schach**. Der Spieler ist verpflichtet, seinen König im nächsten Zug aus dem Schach zu befreien. Ist dies nicht möglich, wenn er an der Reihe ist, so ist er **schachmatt**, und das Spiel ist beendet. 

Kein Spieler darf seinen eigenen König direkt oder indirekt in Schach setzen.

Der **Turm** darf in gerader Richtung beliebig weit ziehen:

![Turm ziehen](/images/move_rook.svg "Turm ziehen")

Das **Springer** darf im stumpfen Winkel ein Feld gerade und eines diagonal springen. Zwischen Start- und Zielfeld stehende Figuren werden übersprungen:

![Springer ziehen](/images/move_knight.svg "Springer ziehen")

Der **Läufer** darf diagonal beliebig weit ziehen:

![Läufer ziehen](/images/move_bishop.svg "Läufer ziehen")

Der **Bauer** darf sich nur von der heimatlichen Grundlinie weg bewegen. Ein Feld in gerader Richtung, wenn das Zielfeld frei ist, oder ein Feld diagonal, wenn eine gegnerische Figur geschlagen werden kann:

![Bauer ziehen](/images/move_pawn.svg "Bauer ziehen")

Beim seinem ersten Zug darf der Bauer auch zwei Felder gerade ziehen:

![Bauer erster Zug](/images/move_pawn_first.svg "Bauer erster Zug")

**En Passant:** Zieht der Bauer in seinem ersten Zug 2 Felder weit, kann er von in dieser Runde von einem gegnerischen Bauern auch dann geschlagen werden, wenn dieser auf das Feld zieht, das der Bauer übersprungen hat.

**Umwandeln:** Erreicht ein Bauer eine gegnerische Grundlinie, so kann er diesen in eine Dame, einen Turm, ein Springer oder einen Läufer der eigenen Farbe umwandeln.


### Spielende

**Gewinner** ist der Spieler, der den gegnerischen König als nächstes mit einer Figur schlagen könnte. Dieser bekommt **3 Punkte**. 

**Verlierer** ist der Spieler, dessen König Schachmatt ist. Dieser bekommt **0 Punkte**. 

Der **dritte Spieler** bekommt **1 Punkt**.

Bietet ein Spieler **Remis** an, und stimmen die anderen Spieler zu, so gilt das Spiel als unentschieden, und jeder Spieler bekommt **1 Punkt**.

Kann ein Spieler keinen gültigen Zug mehr machen (**Pattstellung**), oder befinden sich nur noch die drei Könige auf dem Spielfeld, gilt automatisch Remis.

### Notation

Jedes Feld auf dem Brett hat eine eindeutige Bezeichnung. Das Brett ist unterteilt in horizontale (a-m) und vertikale Reihen (1-13) (zwei von drei geraden Richtungen). Horizontale Reihen werden mit Kleinbuchstaben, vertikale Reihen mit Zahlen bezeichnet:

![Notation](/images/notation.svg "Notation")

Um einen Spielzug zu notieren, schreibt man (außer beim Bauern) vor das Zielfeld den Anfangsbuchstaben der gezogenen Figur. Zieht z.B. ein weißes Springer von `d5` nach `g7`, so schreibt man `Sg7`. Gibt es eine gleiche Figur, die auch dorthin hätte ziehen können, so wird entweder der Buchstabe oder die Zahl des Startfelds eingefügt, je nachdem, was sich zur Unterscheidung eignet. Steht z.B. das zweite weiße Springer auf `d6`, so muss es heissen `S6g7` (und nicht etwa `Sdg7`, da ja beide von `d` kommen).

Um anzugeben, dass eine gegnerische Figur geschlagen wird, schreibt man vor das Zielfeld ein `x`, also z.B. `S6xg7` (Springer auf `6` schlägt Figur auf `g7`).

Wird ein Bauer umgewandelt, so steht am Ende der Anfangsbuchstabe der eingetauschten Figur, also z.B. `i4D` (Bauer zieht nach i4 und wird gegen die Dame eingetauscht).

Ein Remisangebot wird mit `=` notiert.

Eine kleine Rochade (`Ka2`, `Kl7` oder `Kg13`) wird mit `0-0` notiert, eine große Rochade (`Ka7`, `Kg2` oder `Kl13`) mit `0-0-0`.

Wird ein König ins Schach gestellt, so schreibt man ein `+` hinter das Zielfeld, z.B. `Ta5+` (Turm zieht nach `a5` und bedroht den König). Schachmatt wird durch `++` bezeichnet, z.B. `Lb6++` (Läufer zieht nach `b6` und setzt den König schachmatt).

Vor jede neue Runde (beginnend mit weiss) wird eine fortlaufende Nummer geschrieben. Ein Spielprotokoll könnte also so aussehen:

    1. 7d9 2. Sj8 3. 12k10
    4. Le8 5. Sg7 6. Sd5
    ...
    37. Dk6++

Wer auf eine etwas Fehler-tolerantere Notation Wert legt, kann auch immer das Startfeld mit aufschreiben. 

## Kurzregeln
(Kenntnis der klassischen Schachregeln wird vorausgesetzt)

### Aufstellung
- weiss: `a1`-`a8`
- braun: `f1`-`m8`
- schwarz: `f13`-`m13`

Es gibt 9 statt 8 Bauern. Der Springer steht immer rechts vom Läufer. Die Dame steht rechts vom König auf eigener Farbe.

### Spielzüge

**Reihenfolge**: weiss - braun - schwarz 

**Gerade**: über benachbarte Felder 
**Diagonal**: entlang Felder gleicher Farbe 
 
Um diagonal zwischen zwei Felder hindurch zu ziehen, muss eins davon frei sein.

Der **Bauer** kann gerade in 2 Richtungen laufen und diagonal in 3 Richtungen schlagen (von der Grundlinie weg).

Der **Springer** springt ein Feld gerade und eins diagonal (im stumpfen Winkel) 

### Spielende

**Gewinner** ist der Spieler, der als nächstes einen der gegnerischen Könige mit einer Figur schlagen könnte. Dieser bekommt **3 Punkte**. 

**Verlierer** ist der Spieler, dessen König Schachmatt ist. Dieser bekommt **0 Punkte**. 

Der dritte Spieler bekommt **1 Punkt**.

Bietet ein Spieler **Remis** an, und stimmen die anderen Spieler zu, so gilt das Spiel als unentschieden, und jeder Spieler bekommt **1 Punkt**.

Kann ein Spieler keinen gültigen Zug mehr machen (**Pattstellung**), oder befinden sich nur noch die drei Könige auf dem Spielfeld, gilt automatisch **Remis**.

## Bauanleitung


### Material

- Zwei identische Sätze Spielfiguren (z.B. Weiss - Schwarz)
- 1 Dose Lack in einer dritten Farbe (z.B. Braun)
- Material für ein Spielbrett (z.B. Holz und Farbe)

### Herstellung der Figuren

Pro Farbe werden neun Bauern gebraucht. Die Figuren für zwei Farben brauchen nur herausgesucht werden. Für die dritte Farbe werden aus den übrigen Figuren entsprechende herausgesucht und angemalt.

        
![Turm](/images/black_rook.svg "Turm")
![Turm](/images/black_rook.svg "Turm")
![Läufer](/images/black_bishop.svg "Läufer")
![Läufer](/images/black_bishop.svg "Läufer")
![Springer](/images/black_knight.svg "Springer")
![Springer](/images/black_knight.svg "Springer")
![König](/images/black_king.svg "König") 
![Dame](/images/black_queen.svg "Dame")

![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
... für Schwarz

![Turm](/images/white_rook.svg "Turm")
![Turm](/images/white_rook.svg "Turm")
![Läufer](/images/white_bishop.svg "Läufer")
![Läufer](/images/white_bishop.svg "Läufer")
![Springer](/images/white_knight.svg "Springer")
![Springer](/images/white_knight.svg "Springer")
![König](/images/white_king.svg "König") 
![Dame](/images/white_queen.svg "Dame")

![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
... für Weiss

![Turm](/images/black_rook.svg "Turm")
![Turm](/images/black_rook.svg "Turm")
![Läufer](/images/black_bishop.svg "Läufer")
![Läufer](/images/black_bishop.svg "Läufer")
![Springer](/images/black_knight.svg "Springer")
![Springer](/images/black_knight.svg "Springer")
![König](/images/black_king.svg "König") 
![Dame](/images/black_queen.svg "Dame")

![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/black_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
... für Braun

Die restlichen Figuren sind übrig und können als Ersatz aufbewahrt werden.

![Turm](/images/white_rook.svg "Turm")
![Turm](/images/white_rook.svg "Turm")
![Läufer](/images/white_bishop.svg "Läufer")
![Läufer](/images/white_bishop.svg "Läufer")
![Springer](/images/white_knight.svg "Springer")
![Springer](/images/white_knight.svg "Springer")
![König](/images/white_king.svg "König") 
![Dame](/images/white_queen.svg "Dame")

![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
![Bauern](/images/white_pawn.svg "Bauer")
... Reserve

### Konstruktion des Spielbretts

Die Größe des Bretts hängt von den Spielfiguren ab. Ganz gut passt die Faustregel, dass die Kantenlänge eines sechseckigen Spielfelds dem Durchmesser des Sockels der größten Spielfigur (Dame oder König) entspricht.

Mit Zirkel und Lineal lässt sich dann recht einfach ein passendes Spielbrett konstruieren:

Zuerst wird ein Kreis mit dem Radius r = 13 x Spielfeld-Kantenlänge gezogen. Dann ein gleich großer Kreis mit seinem Mittelpunkt auf der Linie des ersten Kreises, dann einer mit dem Mittelpunkt auf einem der Schnittpunkte und so weiter, bis es insgesamt 6 Schnittpunkte auf dem ersten Kreis gibt.

![Konstruktion_1](/images/construction_1.svg "Konstruktion_1")
![Konstruktion_2](/images/construction_2.svg "Konstruktion_2")


Nun macht man aus den 6 Punkten ein großes Seckseck und unterteilt die Linien in kleine Abschnitte, so lang wie die obige Spielfeld-Kantenlänge (pro Linie 13 Abschnitte).

![Konstruktion_3](/images/construction_3.svg "Konstruktion_3")

Nun wird es interessant: Ein Lineal wird an die Abschnittmarkierungen angelegt, immer parallel zu einer Seite des Sechsecks. Jetzt lässt sich die (gedachte) Linie wieder in (gedachte) Abschnitte von Länge einer Spielfeld-Kante einteilen. Entsprechende Abschnitte (siehe Zeichnung) werden durchgezogen.

![Konstruktion_4](/images/construction_4.svg "Konstruktion_4")

Das Ganze muss in allen drei Ausrichtungen wiederholt werden. Ergebnis ist dann (hoffentlich!!) das Sechseckmuster des Spielbretts.

![Konstruktion_5](/images/construction_5.svg "Konstruktion_5")
![Konstruktion_6](/images/construction_6.svg "Konstruktion_6")


Kapiert? Nun müssen nur (!) noch die Felder angemalt werden und fertig ist das Dreierschachbrett!!!

![Konstruktion_7](/images/construction_7.svg "Konstruktion_7")
