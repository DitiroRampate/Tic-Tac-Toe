# Tic-Tac-Toe

* This is a Tic-Tac-Toe game implementation using Java for the logic and XML code for the layout. 
* For the game layout, a constraint layout is used to position our components in the layout. 
* Our layout game will contain three TextView and 10 Buttons. 
* Each player will have its own count score and a big banner indicating who is winning in the game. 
* The game does not have any limitations. The players can keep playing until the reset game manually. 
* For the logic of our Tic Tac Toe android game app, we will create a 2 dimensional array for the buttons with the type of Button, then initialize the buttons using findViewById and setOnclickListeners on them by using for loop.
* We will handle the clicks on our playing field, switch between players and implement a method that checks for a winner at the end of each turn, by going through all rows, columns and diagonals of our playing field and checking if one of them has 3 matching fields.
* An integer variable will count each round and stop the game when it reaches 9 rounds and draw the game.
