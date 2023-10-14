# Dreierschach V2.3 (Three-player chess)

![Dreierschach Logo](/images/logo.svg "Dreierschach Logo")

Chess for three players - nearly original on 126 hexagonal fields

[Deutsche Version](README.md)

![Dreierschach Titel](/images/board_wooden_initial.jpg "Dreierschach Titel")

Dreierschach © 2023 by Christian Wahlmann is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

- [Complete game rules](#complete-game-rules)
- [Short rules](#short-rules)
- [Construction of the game board](#construction-of-the-game-board)

## Complete game rules

Three-player chess is a variation of the classic chess game for three players, with the goal of adopting the classic setting and the official rules as 1:1 as possible.

The often criticized problem of 2:1 alliances is countered by a modified distribution of points. It pays to win, and less to be second.

These are the revised game rules in version 2.2.

### Changes V2.2:
- The game ends as soon as one player is checkmate.
- The point distribution (3, 1, 0) rewards mate-setting.
- Conversion is again according to the original chess rules

### Changes V2.3:
- The notation of the fields was fixed. Alike classic chess white now is placed on the fields `a1` to `h1`. 

### Game material

![Wooden Dreierschach game board in play](/images/board_wood_ingame.png "Wooden Dreierschach game board in play")

- a three-colored hexagonal game board with edges 6 by 8 and 42 fields per color [^1]
- 51 game pieces, 17 of them in one color each:

1x ![1 king](/images/white_king.svg "1 king") 
1x ![1 queen](/images/white_queen.svg "1 queen")
2x ![2 rooks](/images/white_rook.svg "2 rooks")
2x ![2 knights](/images/white_knight.svg "2 knights")
2x ![2 bishops](/images/white_bishop.svg "2 bishops")
9x ![9 pawns](/images/white_pawn.svg "9 panws")

[^1]: no coincidence, the question is irrevocably imprinted in the brainwaves of our subconscious mind[^2]

[^2]: yes, 6 times 8 is not 42, but 6 times 9 is not either, and after all there are 9 pawns

### Game setup

Draw lots to determine which player plays which color. Then the pieces are placed on the board as shown in the illustration.

![Game setup](/images/board_setup.svg "Game setup")

From the baseline of each player, the rooks are placed on the outside, the bishop and knight next to them (the knight is always on the right), and the king and queen in the middle (the queen is always to the right of the king on a field of its own color). In front of these pieces are the 9 pawns in a row.

### Start of the game

The object of the game is to checkmate an opponent's king. The colors are drawn at the beginning of the game. The player with the color white starts.

### Course of the game

The players draw one of their pieces in turn. The order is white, brown, black and so on.

When moving, two basic directions are distinguished:

**straight**, di.e. along adjacent fields:

![move straight](/images/move_straight.svg "move straight")

**diagonal**, di.e. along fields of the same color:

![move diagonal](/images/move_diagonal.svg "move diagonal")

To move diagonally between two fields, one of them must be free.

A piece - with the exception of the knight - may only be moved across free fields. If the target field is occupied by an opponent's piece, it is captured, i.e. removed from the board and replaced by the player's own piece.

The **queen** may move straight and diagonally as far as she likes:

![The queens move](/images/move_queen.svg "The queens move")

The **king** may move like the queen, but only one field.:

![The kings move](/images/move_king.svg "The kings move")

A special move is the so-called **castling**: the king moves to one of the rooks, the rook then moves over it.

![Castling](/images/move_rochade.svg "Castling")

Thereby apply:
- All fields between king and rook must be free.
- Neither the king nor any of the fields between the rook and king may be threatened by an opponent's piece.
- Neither the rook nor the king may have been moved before.
- A distinction is made between minor castling (over 2 free fields) and major castling (over 3 free fields).

If a player's king is threatened, it is in **check**. The player is obliged to release his king from check in the next move. If this is not possible on his turn, he is **checkmated** and the game ends.

No player may directly or indirectly place his own king in check.

The **rook** may move as far as it likes in a straight line:

![The rooks move](/images/move_rook.svg "The rooks move")

The **knight** may jump one field straight and one diagonally at an obtuse angle. Pieces standing between the starting and target field are jumped over:

![The knights move](/images/move_knight.svg "The knights move")

The **bishop** may move any distance diagonally:

![The bishops move](/images/move_bishop.svg "The bishops move")

The **pawn** may only move away from the home baseline. One field in a straight direction if the target field is free, or one field diagonally if an opponent's piece can be captured:

![The pawns move](/images/move_pawn.svg "The pawns move")

On its first move, the pawn may move two field straight:

![A pawns first move](/images/move_pawn_first.svg "A pawns first move")

**En Passant:** An opponent's pawn "en passant" can be captured in his this turn even if the own piece moves to the field that the pawn skipped in its first nove.

**Conversion:** If a pawn reaches an opponent's baseline, it may be converted into a queen, rook, knight or bishop of its own color.


### End of the game

The **winner** is the player who could captures the opponent's king with one of his pieces next. This player gets 3 points.

The player whose king is checkmate **looses** the game. He gets no points.

The player that **neither won nor lost** gets 1 point.

If a player offers a **draw**, and the other players agree, the game is considered a draw, and each player gets 1 point.

If a player cannot make a valid move (**stalemate**), or if only the three kings are left on the board, the game is automatically drawn.

### Notation

Each field on the board has a unique designation. The board is divided into vertical colums (`a`-`m`) and horizontal rows (`1`-`13`) (two of three straight directions). Vertical columns are designated with lowercase letters, horizontal rows with numbers:

![Notation](/images/notation.svg "Notation (here: g4")

To record a move, write the initial letter of the piece moved (except for the pawn) in front of the target field. The knight is denoted by an `N`.

For example, if a white knight moves from `d5` to `g7`, write `Ng7`. If there is an identical piece that could also have moved there, either the letter or the number of the starting field is inserted, whichever is more suitable for differentiation. If the second white knight is on `d6`, it is `N5g7` (and not `Ndg7`, since both come from `d`).

To indicate that an opponent's piece is captured, write an x in front of the target field, e.g. `N6xg7` (knight on `6` captures piece on `g7`).

If a pawn is exchanged, the initial letter of the exchanged piece is written at the end, e.g. `d9Q` (pawn moves to `d9` and is exchanged for the queen).

A draw offer is noted with `=`.

A minor castling (`Kb1`, `Km7` oder `Kg12`) is noted with `0-0`, a major castling (`Kg1`, `Km12` oder `Kb8`) with `0-0-0`.

If a king is placed in check, a `+` is written after the target field, e.g. `Re1+` (rook moves to `e1` and threatens the king). Checkmate is denoted by `++`, e.g. `Bf2++` (bishop moves to `f2` and checkmates the king).

A consecutive number is written in front of each new turn (starting with white). So a game protocol could look like this:

    1. gi4 Sd2 11j11
    2. Li7 Sh10 Sj7
    ...
    19. Dg11++

If you prefer a more error-tolerant notation, you can always write down the starting field as well. 

## Short rules
(Knowledge of the classical chess rules is assumed)

### Game setup
- white: `a1`-`h1`
- gray: `h13`-`a6`
- black: `m6`-`m13`

There are 9 instead of 8 pawns. The knight is always to the right of the bishop. The queen is to the right of the king on its own color.

### Moves

**Sequence**: white - gray - black 

**Straight**: across adjacent fields
**Diagonal**: along fields of the same color

To move diagonally between two fields, one of them must be free.

The **pawn** can move straight in 2 directions and capture diagonally in 3 directions (away from the baseline).

The **knight** jumps one field straight and one diagonally (at an obtuse angle).

### End of the game

The **winner** is the player who could captures the opponent's king with one of his pieces next. This player gets 3 points.

The player whose king is checkmate **looses** the game. He gets no points.

The player that **neither won nor lost** gets 1 point.

If a player offers a **draw**, and the other players agree, the game is considered a draw, and each player gets 1 point.

If a player cannot make a valid move (**stalemate**), or if only the three kings are left on the board, the game is automatically drawn.

## Building instructions

### Material

- Two identical sets of game pieces (e.g. white - black)
- 1 can of paint in a third color (e.g. brown)
- Material for a game board (e.g. wood and paint)

### Making the pieces

Nine pawns are needed per color. The pieces for two colors only need to be picked out. For the third color, corresponding figures are picked out from the remaining ones and painted.

![rook](/images/black_rook.svg "rook")
![rook](/images/black_rook.svg "rook")
![bishop](/images/black_bishop.svg "bishop")
![bishop](/images/black_bishop.svg "bishop")
![knight](/images/black_knight.svg "knight")
![knight](/images/black_knight.svg "knight")
![king](/images/black_king.svg "king") 
![queen](/images/black_queen.svg "queen")

![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
... black pieces

![rook](/images/white_rook.svg "rook")
![rook](/images/white_rook.svg "rook")
![bishop](/images/white_bishop.svg "bishop")
![bishop](/images/white_bishop.svg "bishop")
![knight](/images/white_knight.svg "knight")
![knight](/images/white_knight.svg "knight")
![king](/images/white_king.svg "king") 
![queen](/images/white_queen.svg "queen")

![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
... white pieces

![rook](/images/black_rook.svg "rook")
![rook](/images/black_rook.svg "rook")
![bishop](/images/black_bishop.svg "bishop")
![bishop](/images/black_bishop.svg "bishop")
![knight](/images/black_knight.svg "knight")
![knight](/images/black_knight.svg "knight")
![king](/images/black_king.svg "king") 
![queen](/images/black_queen.svg "queen")

![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/black_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
... gray pieces

The remaining figures are left and can be kept as spares.

![rook](/images/white_rook.svg "rook")
![rook](/images/white_rook.svg "rook")
![bishop](/images/white_bishop.svg "bishop")
![bishop](/images/white_bishop.svg "bishop")
![knight](/images/white_knight.svg "knight")
![knight](/images/white_knight.svg "knight")
![king](/images/white_king.svg "king") 
![queen](/images/white_queen.svg "queen")

![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
![pawnn](/images/white_pawn.svg "pawn")
... reserve

### Construction of the game board

The size of the board depends on the game pieces. The rule of thumb that the edge length of a hexagonal game board corresponds to the diameter of the base of the largest game piece (queen or king) fits quite well.

Using a compass and a ruler, it is then quite easy to construct a suitable game board:

First, draw a circle with radius `r = 13 x board edge length`. Then a circle of the same size with its center on the line of the first circle, then one with its center on one of the intersection points, and so on until there are a total of 6 intersection points on the first circle.

![Construction_1](/images/construction_1.svg "Construction_1")
![Construction_2](/images/construction_2.svg "Construction_2")

Now make a large hex out of the 6 points and divide the lines into small sections, as long as the board edge length above (13 sections per line).

![Construction_3](/images/construction_3.svg "Construction_3")

Now it gets interesting: A ruler is placed at the section markings, always parallel to one side of the hexagon. Now the (imaginary) line can be divided again into (imaginary) sections of length of one edge of the playing field. Corresponding sections (see drawing) are drawn through.

![Construction_4](/images/construction_4.svg "Construction_4")

The whole thing must be repeated in all three orientations. The result is then (hopefully!!) the hexagon pattern of the board.

![Construction_5](/images/construction_5.svg "Construction_5")
![Construction_6](/images/construction_6.svg "Construction_6")


Got it? Now only (!) the fields have to be painted and the three-chessboard is ready!!!

![Konstruktion_7](/images/construction_7.svg "Konstruktion_7")
