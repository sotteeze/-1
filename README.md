# Tic Tac Toe C++
Tic Tac Toe C++
This project implements a simple game "Tic Tac Toe" in C++ for two players. One player puts a cross, and the other puts a zero. The winner is the player who first finds a line (horizontally, parallel, diagonally) of crosses or zeros. There is a draw in the game, if all the cells of the field are occupied, and none of the players has collected a line, then there is a draw.
## Futures 
- Board Display: Shows the current state of the board.
- Player Moves: Player makes his move
- Win/Loss Checks Determines whether a player has won or lost
- Score Tracking: Reads and writes win/loss statistics from/to a file.
- Save Logs Saves all actions that have been performed in the game

## This array h consists of 9 characters, each initialized with a '-' character. This array is probably a game board or some kind of data structure that needs to be filled with default values.

![image](https://github.com/sotteeze/-1/assets/132690771/36f0aae5-42e0-432d-a14e-6f55783583f6)

## The cleanboard() function is designed to clear the screen. It prints 50 empty lines using a for loop that prints the newline "\n" 50 times.

![image](https://github.com/sotteeze/-1/assets/132690771/5d296e0d-27e6-43ec-a356-2d83d45d5004)

## This function displays a static game board with cell numbers from 1 to 9. Presumably, this function is called to display the initial state of the game board.

![image](https://github.com/sotteeze/-1/assets/132690771/a59dc796-3ba7-4439-93a6-2ce661b7fc38)

## This function displays the current state of the playing field using the values ​​from the h array. This allows you to see changes on the playing field as players make their moves.

![image](https://github.com/sotteeze/-1/assets/132690771/e829881c-0daf-44c6-bbe3-fe5f66e0c1a2)

## This function is responsible for receiving the move from the user. It reads the entered number and checks whether it is valid (in the range from 1 to 9 and points to an empty cell). If the input is invalid, the function displays an error message and prompts for input again until a valid value is entered.

![image](https://github.com/sotteeze/-1/assets/132690771/b240a049-ac7e-4a2b-b0f7-27df241960f3)

## This loop is performed 9 times, which corresponds to the maximum number of moves in a tic-tac-toe game (3x3 = 9 squares).

![image](https://github.com/sotteeze/-1/assets/132690771/719fda65-2d74-419a-b070-13a916fed9fc)

## These functions are called to update and display the playing field before each move. The cleanboard() function probably clears or updates the state of the board, and board1() and board() display it again.

![image](https://github.com/sotteeze/-1/assets/132690771/fdf23b77-632b-41fd-a41a-ab7fdd7abad1)

## Receives a move from the player. The get_move() function probably asks the user for input to determine which cell he wants to put his sign in (X or O).

![image](https://github.com/sotteeze/-1/assets/132690771/7a3569e2-5b85-4e9b-b536-7ef3ec5837fd)


