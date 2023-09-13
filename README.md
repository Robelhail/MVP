	Python code for a Tic Tac Toe game using the pygame library

made by Robel Hailemichael

        	@@@@@@@@Tic Tac Toe game@@@@@@@@@@

	This game allows you to play against an AI opponent that uses the minimax algorithm to make its moves. The game has a graphical interface and displays messages when the game ends (either you or the computer wins, or it's a draw)

1) The code initializes the pygame library and sets up the game window.

2) It defines a 3x3 game board as a NumPy array where 0 represents an empty cell, 1 represents the computer's move, and -1 represents the player's move.

3) The minimax function is used to implement the minimax algorithm for the computer's moves. It explores all possible moves and selects the best one.

4) The game loop runs indefinitely until you close the game window or exit the program. Inside the loop, it listens for user input (mouse clicks) to make the player's move and updates the game board accordingly.

5)After each move, the game checks for a win or draw condition and displays a corresponding message.

6) If the game is over (either someone wins or it's a draw), it waits for a few seconds and then resets the game board for a new round.

7) ("background.png," "o.png," and "x.png") and the pygame library installed to run this code successfully
