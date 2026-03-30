TIC TAC TOE

This is a simple, command-line Tic-Tac-Toe game built in Python where the opponent is an Arti
ficial Intelligence that will never lose. This project is a perfect introduction to how AI "thinks"
using an algorithm called Minimax.
1.  INSTALLATION & SETUP
The project runs entirely in Python so it is very quick and easy
1.1 PREREQUISITES
You only need python installed on your device
1.2 Running the game
 1. Download the Files: Get all the code files from the project repository.
 2. Open Your Terminal/Command Prompt: Navigate into the project folder using the cd .. command.
3. Run the Game !: Once inside the project folder, execute the main game file using this command:
 python -m ai_tictactoe.main
The game will start, and you will be prompted to make your first move.
 HOW TO PLAY-
 . The game board is displayed in your terminal. It's a standard 3 x 3 grid.
 . You will be prompted to "enter your move (0-8)".
 . The board cells are numbered from 0 (top-left) to 8 (bottom-right), like this:
 <img width="178" height="136" alt="image" src="https://github.com/user-attachments/assets/c0443479-74a8-4e8a-9841-d94d6dc3fc6f" />
 
 . Enter the number corresponding to the empty cell where you want to place your 'X'.
 . The AI will then make its move as 'O'.
 . The goal is simple: try to win, or at least force a draw! (The AI will make it very tough!)
    
 HOW THE AI WORKS

 This project isn't just a game; it's a demonstration of a powerful AI concept called the Minimax Algorithm.
The Problem: The AI's job is to figure out the absolute best move to make.
 The Solution (Minimax): The AI looks ahead at every single possible move you and it could make until
the game ends (a win, loss, or draw).
It Maximizes its own score (aiming for a win, which it scores as high).
 It Minimizes your score (assuming you will always make the move that is worst for it).
The Result: Because it can see the end of every possible path, the AI will always choose
 the move that guarantees it will either win or at worst achieve a draw. It is unbeatable.
