#connect4

This was the submision by Russell Buchanan for the first assignment in ECSE 526 - Artificial Intelligence taght by Jermey Cooperstock in Fall 2015.

Since then it has been modified to only have two modes: AI vs AI and Human vs AI.

#The Rules

Below is the starting configuration. 0's are white and X's are black. White goes first.

  1 2 3 4 5 6 7
1  , , , , , , X,
2 X, , , , , , 0,
3 0, , , , , , X,
4 X, , , , , , 0,
5 0, , , , , , X,
6 X, , , , , , 0,
7 0, , , , , ,  ,


Each play takes turn moving any of their piecse North (upwards), South (downwards), East (to the right) or West (to the left). You cannot move the other player's pieces or move out of bounds. You cannot take or jump over your oponent's pieces.

The game is won when you have four pieces lined up in a row. It can be horizontally, vertically or diagonally.

#To Run

Simply run the python script and follow the directions.
