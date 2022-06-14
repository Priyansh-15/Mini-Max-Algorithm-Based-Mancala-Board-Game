# Project Name : Mini-Max-Algorithm-Based-Mancala-Board-Game
# Made By - Priyansh Sharma

* The mancala games are a family of two-player turn-based strategy board games played
with small stones, beans, or seeds and rows of holes or pits in the earth, a board or other
playing surface. The objective is usually to capture all or some set of the opponent's
pieces.

![image](https://user-images.githubusercontent.com/77832407/173486391-67c79964-5113-44fc-a588-dc4ce57054b6.png)

* I tried to Implement ***Mancala game*** using ***Mini-Max Algorithm and Alpha-Beta pruning*** .

![image](https://user-images.githubusercontent.com/77832407/173486691-ad64aa3b-36ee-436e-bebc-f5f08ac71405.png)

# Mini-Max Algorithm (Alpha Beta Pruning)

* ***Alpha Beta pruning*** is an optimization technique for min-max algorithms that would
reduce the number of branch / node extensions to get better and faster results. In this
project we are implementing the famous African board game “Mancala” using the
min-max algorithm (Alpha Beta Pruning).

* ***Minimax is a kind of backtracking algorithm*** that is used in decision making and game
theory to find the optimal move for a player, assuming that your opponent also plays
optimally. It is widely used in two player turn-based games such as Tic-Tac-Toe,
Backgammon, Mancala, Chess, etc.

* ***In Minimax the two players are called maximizer and minimizer. The maximizer tries to
get the highest score possible while the minimizer tries to do the opposite and get the
lowest score possible.***

* Every board state has a value associated with it. In a given state if the maximizer has the
upper hand then, the score of the board will tend to be some positive value. If the
minimizer has the upper hand in that board state then it will tend to be some negative
value. The values of the board are calculated by some heuristics which are unique for
every type of game.

# Mancala Board Representation 

![image](https://user-images.githubusercontent.com/77832407/173488829-32df6607-8f15-4314-b562-b3401f4779f0.png)

* Both the player will have 6 cups each containing 4 stones each . ***For Player 1 it will be from index 1 to 6 and for Player 2 it will be from index 8 to 13 .***

* ***The Mancala box for Player 1 will be at Index 7 and for player 2 will be at Index 0 .***


# Result and Game Representation 

* We tried to make 2 type of gameplay (i) Player Vs Player  (ii) Player Vs AI(Bot) .

* ***The final result of game will be calculated on the basis of which player have a sum total of stones in their mancala box more compared to other .***
![image](https://user-images.githubusercontent.com/77832407/173490160-7bbe96b6-819e-4166-b4bc-1e8dafd7659f.png)

![image](https://user-images.githubusercontent.com/77832407/173490177-633a25a1-c639-4941-94eb-6b6c4749af81.png)

![image](https://user-images.githubusercontent.com/77832407/173490194-6fbb9210-b4ed-4e28-a9b5-234a1479a008.png)

![image](https://user-images.githubusercontent.com/77832407/173490205-5e4e22b8-5a21-47f5-bd08-020553a9276e.png)

