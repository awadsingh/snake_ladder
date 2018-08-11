# snake_ladder
------------------
snake_ladder_hld
------------------
Q1:  How to identified calsses from use case.

go through use and case find out nouns.
1. game have square baord.
two nouns are mentined "game" & "board".

2. board have number of square.
 board
3. square is either snake are ladder type
   snake square  ladder square
4. all player are added to start square.
   player, start square
5.  player represent by color piece.
   piece
5. when any player reach to last/win square game over.
  win square.

in above use case we find out below classes.
game
board
square  (start , win ,snake ,ladder will use in dld)
player.
piece.

Q2 . How to indetified relation in classes.

Ans : go through use case and find relation.

game have board and player (game have board pointer and player list).


square have no of square (square class have list or array of square).

player have piece (each player have piece pointer).

class and realation shown in hld diagram.


