## Features
- **Chess Board Representation**: Implements a simple yet effective chess board representation for easy move generation and piece tracking.
- **Move Generation**: Supports legal move generation for all chess pieces (Pawns, Knights, Bishops, Rooks, Queens, and Kings).
- **Simple AI**: The engine uses search algorithms MiniMax, Alpha Beta Pruning and Monte Carlo Tree Search to evaluate the best move in a given position.
- **Board Evaluation**: Implements a basic evaluation function to assess the quality of a board position based on material count and piece activity.
- **User Interaction**: Allows users to play against the AI, with a GUI.
- **Game Rules Implementation**: Includes standard chess rules, such as castling, en passant, and pawn promotion.
- **Customizable Difficulty**: The AI's depth of search can be adjusted to change its difficulty level.
- **Endgame Detection**: Identifies checkmate, stalemate, and draw conditions, ending the game appropriately.


The AI will generate moves and challenge you to a game of chess. You can modify the AI's depth of analysis and its strategy in the code.

## Project Structure
- `ChessAI.py`: Contains the main logic for generating moves and evaluating the board.
- `ChessEngine.py`: Implements core chess engine functionalities such as board setup, move generation, and game rules.
- `ChessMain.py`: The entry point of the program to interact with the chess engine.
- `requirements.txt`: Lists the dependencies (if any) for the project.


## Contributing
Feel free to fork this repository, submit issues, and make pull requests. Contributions to improve the AI's performance and strategy are welcome!

For any issues or inquiries, please open an issue in the GitHub repository.
