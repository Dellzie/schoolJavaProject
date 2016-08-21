# schoolJavaProject
The Task
Plan and implement a program that allows two users to play games of 'PILES'. This game involves players taking turns to remove counters (any amount) from one of a number of piles. The player to take the last counter is the winner. (It sounds simple, but it can be tricky to play!)

Your program must allow the players to set-up the game:
Enter their names (to personalise the play)
Choose how many games to play (1 or more)
The piles should be setup:
Five piles
Random number of counters in each pile (1 to 5)
A player should be then selected to go first.
On each go, the player must be asked to:
Pick which pile to take from (1 to 5)
Pick how many counters to remove from the pile
After each go, the program should:
Display the state of the piles
Check to see if the player has won
If there are still piles with counters remaining, play continues until a win occurs.
Points are awarded to winning players, and at the end of the specified number of games, the final scores should be shown, along with a winner being declared (if any).


Game Plan
The following is an abstract plan for the game that can be used as the basis for your program…
Constants and Variables
Note: The scope and type of variables and constants is to be determined by the student
Examples of possible constants:
MIN_GAMES
MAX_PILE_SIZE
etc...
Examples of possible variables:
player1name
player2name
currentPlayer
gameCount
etc…
Indexed Data Structure
An indexed data structure (array) could be used for:
The piles
The names of the players
etc...
Example Test Cases and Outcomes
Note: it is left to the student to come up with a full set of test cases that thoroughly test the program inputs and game logic
Player 1 name: Bob
Player 2 name: Ann
Games to play: 1


Starting state of the piles: 		1:5   2:3   3:5   4:1   5:3


Bob's go: 3 from pile 2 	→ 	1:5   2:0   3:5   4:1   5:3
Ann's go: 4 from pile 1 	→ 	1:1   2:0   3:5   4:1   5:3
Bob's go: 5 from pile 3 	→ 	1:1   2:0   3:0   4:1   5:3
Ann's go: 3 from pile 5 	→ 	1:1   2:0   3:0   4:1   5:0
Bob's go: 1 from pile 1 	→ 	1:0   2:0   3:0   4:1   5:0
Ann's go: 1 from pile 4 	→ 	1:0   2:0   3:0   4:0   5:0


No counters left. Ann took the last counter, so Ann wins and gains 1 point


Ann is declared overall winner
