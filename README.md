# snake_ladder

before going to attempt any design realted quaetion first we have write
use case story.
use case story always help to identified class an their realtionship.

------------------
use case
------------------
1. game have square baord
2. board have number of square
3. square is either snake are ladder type
4. all player are added to start square.
5. player can be human or computer
6. when any player reach to last/win square game over.


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

identified classes.
1. game
2. board
3. square (start , win ,snake ,ladder will use in dld)
4. player.
5. piece.

Q2 . How to indetified relation in classes.

 Ans : go through use case and find relation.

 1. game have board and player (game have board pointer and player list).
 2. square have no of square (square class have list or array of square).
 3. player have piece (each player have piece pointer).
 4. class and realation shown in hld diagram.

--------------------------------
dld coming soon
--------------------------------
