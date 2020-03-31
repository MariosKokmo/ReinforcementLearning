# ReinforcementLearning
A repository for training and demonstrative purposes

In the following chapters we will try to implement different AI agents using a variety of algorithms.
The mini-projects will be based on the development timeline in the book of Sutton and Barto.

The Tic-Tac-Toe game consists of an RL-trained agent that becomes able to play the game through
gaining experience while playing against a similar agent-copy of itself. Once trained, the agent
can play against the human player.
The project consists of three classes (agent, human, environment).
The rules are simple and well-known, you have to put 3 of your own symbols in a row whether that is a proper row,
column, or one of the diagonals.
The board is a classic 3 by 3, but can be easily modified to be a larger one. In that case the game takes longer, but
the difficulty remains the same.


![TicTacToe](300px-Tic_tac_toe.svg[1].png)
(example of a tic tac toe board (wikipedia))

Each state can be represented as a number in a base-3 system. For example, starting from the top left and crossing the rows towards the right before going to the next one, if we consider an empty slot to be represented by the number 0, a slot with an 'x' in it as 1 and with a 'o' in it as 2, then an 'x' at the top left corner and the rest of the board empty would be represented as 100000000 etc.
