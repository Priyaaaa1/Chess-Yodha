# Chess Yodha ♟️

A web-based chess game with an intelligent AI opponent powered by Minimax and Alpha-Beta Pruning.

## ✨ Features

* **Interactive Chessboard:** A visually appealing and responsive chessboard where you can make your moves.
* **Comprehensive Piece Movement:** Correct implementation of moves for all chess pieces (Pawn, Rook, Knight, Bishop, Queen, King).
* **Special Chess Rules:**
    * **Castling:** Both Kingside and Queenside castling are supported.
    * **En Passant:** The special pawn capture move is fully implemented.
    * **Pawn Promotion:** Pawns reaching the opposite end of the board automatically promote to a Queen (simplified for now).
* **AI Opponent:** Play against a bot that uses the **Minimax algorithm with Alpha-Beta Pruning** to determine its moves.
* **Adjustable Difficulty:** Currently fixed to "Hard" mode for the AI's search depth.
* **Game State Management:** Tracks current player, selected pieces, castling rights, en passant targets, and checks for game-ending conditions.
* **Game End Conditions:**
    * **Check:** Notifies when a King is in check.
    * **Checkmate:** Declares a winner when a King is checkmated.
    * **Stalemate:** Declares a draw in case of a stalemate.
* **Move History:** Tracks and displays all moves made in the game.
* **Captured Pieces Display:** Shows the pieces captured by each player.
* **Undo Functionality:** Allows you to revert to previous game states.
* **Responsive Design:** Styled with Tailwind CSS for a consistent experience across different screen sizes.

## 🚀 Technologies Used

* **HTML5:** For the basic structure of the web pages.
* **CSS3:** Custom styles to enhance the visual appeal, including animations.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and responsiveness.
* **JavaScript (ES6+):** Powers all game logic, AI, and DOM manipulation.

## 🎮 How to Play

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/chess-yodha.git](https://github.com/YourUsername/chess-yodha.git)
    ```
    (Replace `YourUsername` with your actual GitHub username)
2.  **Navigate to the Project Directory:**
    ```bash
    cd chess-yodha
    ```
3.  **Open `index.html`:**
    Simply open the `index.html` file in your preferred web browser.
4.  **Start a Game:**
    On the home screen, click "Play Game" to start a new match against the AI.
5.  **Make Your Move:**
    * Click on a piece you want to move. Possible moves will be highlighted.
    * Click on the target square to complete your move.
6.  **New Game:**
    Click the "New Game" button to reset the board and start over.
7.  **Undo Move:**
    Click the "Undo Move" button to revert the last player and AI moves.

## 🤝 Contribution

This project was developed by:

* **[Nayan Pandey](https://github.com/nayan-095)** 
* **[Priya Tiwari](https://github.com/Priyaaaa1)** 

We welcome suggestions and improvements! If you have any ideas, feel free to open an issue or submit a pull request.

## 🔮 Future Enhancements (Possible features)

* Add more sophisticated draw conditions (Fifty-move rule, Threefold repetition, Insufficient material).
* Implement a UI for pawn promotion selection (instead of automatic Queen promotion).
* Introduce multiple AI difficulty levels (Easy, Medium).
* Customizable board themes and piece styles.
* Online multiplayer functionality.
* Tutorials and advanced chess puzzles.
* User profiles and progress tracking.


---

© 2025 Chess Yodha Inc.
