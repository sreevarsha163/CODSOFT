# Tic-Tac-Toe AI
This project is an implementation of the classic Tic-Tac-Toe game, where a human player can play against an unbeatable AI. The AI uses the Minimax algorithm with Alpha-Beta Pruning to make optimal moves, ensuring it either wins or forces a tie.

## Features
- **Unbeatable AI:** The AI is designed to be unbeatable using the Minimax algorithm, making the game challenging and fair.
- **Human vs AI:** The game allows a human player to compete against the AI.
- **Efficient Algorithm:** The implementation includes Alpha-Beta Pruning to optimize the Minimax algorithm, reducing the number of nodes that need to be evaluated.

## How to Run
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/tic-tac-toe-ai.git
    cd tic-tac-toe-ai
    ```

2. **Run the game:**
    Make sure you have Python installed on your system. You can then run the game by executing the following command:

    ```bash
    python tictactoe.py
    ```

3. **Play the game:**
    - The game will display an empty Tic-Tac-Toe board in the terminal.
    - You (the human player) will be prompted to enter your move by specifying a number between 1 and 9, corresponding to the board positions:
      ```
      1 | 2 | 3
      4 | 5 | 6
      7 | 8 | 9
      ```
    - The AI will automatically make its move after yours. The game continues until there is a winner or the game ends in a tie.


## Project Structure
- **`tictactoe.py`**: The main script that contains the game logic, including the implementation of the Minimax algorithm with Alpha-Beta Pruning.

## How It Works
The AI uses the Minimax algorithm to evaluate possible moves and choose the best one. Alpha-Beta Pruning is applied to minimize the number of nodes evaluated, making the algorithm more efficient. 

- **Minimax Algorithm:**
   The AI simulates all possible moves to determine the best outcome. It tries to maximize its own chances of winning while minimizing the human player's chances.
  
- **Alpha-Beta Pruning:**
   This optimization technique skips unnecessary evaluations, speeding up the decision-making process.

## Requirements
- Python 3.x
-No additional libraries are required to run this project.

## Code 
![Screenshot 2024-09-01 131551](https://github.com/user-attachments/assets/8af80f32-0dff-4668-bc73-bcbb8e1d337a)
![Screenshot 2024-09-01 132422](https://github.com/user-attachments/assets/534e2d07-0212-4994-8e17-ca5fb2f52ecc)
![Screenshot 2024-09-01 132737](https://github.com/user-attachments/assets/399289f1-5ee0-4923-be19-ccbd71d96848)
![Screenshot 2024-09-01 132938](https://github.com/user-attachments/assets/b4c9287f-5188-4140-811a-9aa7dc58a413)
![Screenshot 2024-09-01 133150](https://github.com/user-attachments/assets/da2a5237-07be-4444-8fb8-1063aeeba9d0)

## Output
![Screenshot 2024-09-01 133548 (2)](https://github.com/user-attachments/assets/a05b68bb-6d4b-47df-bf46-efad483218cc)
![Screenshot 2024-09-01 134923](https://github.com/user-attachments/assets/8d3d4a19-10c3-4fe2-96d9-035668a1ee3b)
