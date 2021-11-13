# dreierschach V2.2
Schach zu dritt - chess for three players - nah am Original auf 126 hexagonalen Feldern - nearly original on 126 hexagonal fields

Dreierschach © 2021 by Christian Wahlmann is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

## Vollständige Spielregeln
### Spielmaterial

- ein Spielbrett mit 126 sechseckigen Feldern in drei Farben 
- 51 Spielfiguren, davon je 17 in einer Farbe: 

![1 König](/white_king.svg "1 König") 
![1 Dame](/white_queen.svg "1 Dame")
![2 Türme](/white_rook.svg "2 Türme")
![2 Pferde](/white_knight.svg "2 Springer")
![2 Läufer](/white_bishop.svg "2 Läufer")
![9 Bauern](/white_pawn.svg "9 Bauern")

### Spielvorbereitung

Es wird ausgelost, welcher Spieler welche Farbe spielt. Dann werden die Figuren wie in der Abbildung auf das Spielbrett gestellt. Von der Grundlinie des jeweiligen Spielers aus stehen die Türme außen, daneben Läufer und Pferd (wobei das Pferd immer rechts steht), und in der Mitte König und Dame (sie steht immer rechts vom König auf einem Feld ihrer eigenen Farbe). Vor diesen Figuren stehen die 9 Bauern in einer Reihe.

### Spielziel

Ziel des Spiels ist es, den König eines Gegners Schachmatt zu setzen (s.u.). Dabei wird abwechselnd je eine Figur gezogen. Weiß beginnt, danach ist Braun an der Reihe, dann Schwarz, und immer so weiter.

### Spielverlauf

Beim Ziehen werden zwei grundsätzliche Richtungen unterschieden: gerade, d.h. entlang benachbarter Felder und diagonal, d.h. entlang gleichfarbiger Felder.
- Um diagonal zwischen zwei Feldern hindurchziehen zu können, muss eines davon frei sein. 
- Eine Figur darf - mit Ausnahme des Pferdes - nur über freie Felder gezogen werden. Ist das Zielfeld von einer gegnerischen Figur besetzt, so wird diese geschlagen, d.h. vom Brett genommen und durch die eigene ersetzt. 
      
Ein besonderer Zug ist die sogenannte Rochade: der König zieht an einen der Türme heran, der Turm setzt dann über ihn hinweg. Dabei gilt:
- Alle Felder zwischen König und Turm müssen frei sein. 
- Weder König noch eines der Felder zwischen Turm und König dürfen durch eine gegnerische Figur bedroht sein. 
- Weder Turm noch König dürfen schon einmal bewegt worden sein. 
- Man unterscheidet zwischen kleiner Rochade (über 2 freie Felder) und großer Rochade (über 3 freie Felder). 

Der Bauer darf sich nur von der heimatlichen Grundlinie weg bewegen. Ein Feld in gerader Richtung, wenn das Zielfeld frei ist, oder ein Feld diagonal, wenn eine gegnerische Figur geschlagen werden kann.

En Passant: Zieht der Bauer in seinem ersten Zug 2 Felder weit, kann er von in dieser Runde von einem gegnerischen Bauern auch dann geschlagen werden, wenn dieser auf das Feld zieht, das der Bauer übersprungen hat.

Umwandeln: Erreicht ein Bauer eine gegnerische Grundlinie, so kann er diesen in eine Dame, einen Turm, ein Pferd oder einen Läufer der eigenen Farbe umwandeln.
Wird der König eines Spielers bedroht, so ist er im Schach. Der Spieler ist verpflichtet, seinen König im nächsten Zug aus dem Schach zu befreien. Ist dies nicht möglich, wenn er an der Reihe ist, so ist er schachmatt, und das Spiel ist beendet. 
Kein Spieler darf seinen eigenen König direkt oder indirekt in Schach setzen.

### Spielende

Gewinner ist der Spieler, der den gegnerischen König als nächstes mit einer Figur schlagen könnte. Dieser bekommt 3 Punkte. 
Verlierer ist der Spieler, dessen König Schachmatt ist. Dieser bekommt 0 Punkte. 
Der dritte Spieler bekommt 1 Punkt.

Bietet ein Spieler Remis an, und stimmen die anderen Spieler zu, so gilt das Spiel als unentschieden, und jeder Spieler bekommt 1 Punkt.
Kann ein Spieler keinen gültigen Zug mehr machen (Pattstellung), oder befinden sich nur noch die drei Könige auf dem Spielfeld, gilt automatisch Remis.

### Notation

Jedes Feld auf dem Brett hat eine eindeutige Bezeichnung. Das Brett ist unterteilt in horizontale (a-m) und vertikale Reihen (1-13) (zwei von drei geraden Richtungen). Horizontale Reihen werden mit Kleinbuchstaben, vertikale Reihen mit Zahlen bezeichnet. 
Um einen Spielzug zu notieren, schreibt man (außer beim Bauern) vor das Zielfeld den Anfangsbuchstaben der gezogenen Figur. Zieht z.B. ein weißes Pferd von d5 nach g7, so schreibt man Pg7. Gibt es eine gleiche Figur, die auch dorthin hätte ziehen können, so wird entweder der Buchstabe oder die Zahl des Startfelds eingefügt, je nachdem, was sich zur Unterscheidung eignet. Steht z.B. das zweite weiße Pferd auf d6, so muss es heissen P6g7 (und nicht etwa Pdg7, da ja beide von d kommen).

Um anzugeben, dass eine gegnerische Figur geschlagen wird, schreibt man vor das Zielfeld ein x, also z.B. P6xg7 (Pferd auf 6 schlägt Figur auf g7).

Wird ein Bauer umgewandelt, so steht am Ende der Anfangsbuchstabe der eingetauschten Figur, also z.B. i4D (Bauer zieht nach i4 und wird gegen die Dame eingetauscht). Ein Remisangebot wird mit = notiert.
Eine kleine Rochade (mit Ta8, Tf1 oder Tm13) wird mit 0-0 notiert, eine große Rochade (mit Ta1, Tm8 oder Tf13) mit 0-0-0.
Wird ein König ins Schach gestellt, so schreibt man ein + hinter das Zielfeld, z.B. Ta5+ (Turm zieht nach a5 und bedroht den König). Schachmatt wird durch ++ bezeichnet, z.B. La5++ (Läufer zieht nach a5 und setzt den König schachmatt).
Vor jede neue Runde (beginnend mit weiss) wird eine fortlaufende Nummer geschrieben. Ein Spielprotokoll könnte also so aussehen:

    1. 4d4 Pe10 ll9 2. 8d8 Peh11 Tj8 3. Le5 ge10 mm11 4. Lxg3 kj11 (...) 20. Pi13++

Wer auf eine etwas Fehler-tolerantere Notation Wert legt, kann auch das Startfeld aufschreiben. So kann man das Spiel auch bei einem Tippfehler noch nachvollziehen. 

## Kurzregeln
(Kenntnis der klassischen Schachregeln wird vorausgesetzt)

### Aufstellung
- weiss: a1-a8 
- braun: f1-m8 
- schwarz: f13-m13 
- 
Es gibt 9 statt 8 Bauern. Das Pferd steht immer rechts vom Läufer. Die Dame steht rechts vom König auf eigener Farbe.

### Spielzüge
- Reihenfolge: weiss - grau - schwarz 
- Gerade: über benachbarte Felder 
- Diagonal: entlang Felder gleicher Farbe 
- 
Um diagonal zwischen zwei Felder hindurch zu  ziehen, muss eins davon frei sein.

Bauer:
- gerade in 2 Richtungen laufen 
- diagonal in 3 Richtungen schlagen (von der Grundlinie weg) 

Pferd:
- springt ein Feld gerade und eins diagonal (im stumpfen Winkel) 

### Spielende

Gewinner ist der Spieler, der als nächstes einen der gegnerischen Könige mit einer Figur schlagen könnte. Dieser bekommt 3 Punkte. 
Verlierer ist der Spieler, dessen König Schachmatt ist. Dieser bekommt 0 Punkte. 
Der dritte Spieler bekommt 1 Punkt.

Bietet ein Spieler Remis an, und stimmen die anderen Spieler zu, so gilt das Spiel als unentschieden, und jeder Spieler bekommt 1 Punkt.
Kann ein Spieler keinen gültigen Zug mehr machen (Pattstellung), oder befinden sich nur noch die drei Könige auf dem Spielfeld, gilt automatisch Remis.
