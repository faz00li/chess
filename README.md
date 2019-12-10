https://www.markdownguide.org/cheat-sheet/

# Chess

#### Two Player Chess GetMakeModel

#### By faz00li

## Description

first stages of implementing chess game.

## Features in current sprint

checking if queen can attack a rival's piece

## To DO

### create Board class
* 8 by 8 grid
* BoardSetup() -> place queen and rival's piece
* Turn() -> check if queen can attack
* PrintBoard() -> print board

### create Piece class
* field coordinate x
* field coordinate y

### create Queen class inherit from Piece
* CheckAttack(rivalPiece) -> check if queen can attack rival's piece
  * horizontal, vertical, diagonal
* Turn() -> check if queen can attack


### UI
* Enter Location of queen
* Enter Location of rival Piece
* Display if queen can attack

## Program
* prompt user for coordinates of queen and rp
* pass info to BoardSetup()
* create instance of queen and rp
* print board w/ queen and rp
* print can/cant attack
* re-prompt

Copyright (c) 201 **_faz00li_**
