# Tic-Tac-Toe-Web-Game
A sleek, neon-themed Tic Tac Toe web application built with a focus on clean UI and an unbeatable AI.

##  Features

* **Dual Game Modes**: Play against a friend locally or challenge the computer.
* **Intelligent AI**: The "Hard" difficulty uses the **Minimax algorithm**, making it theoretically impossible to beat.
* **Variable Difficulty**: Choose between **Easy**, **Medium**, and **Hard** to match your skill level.
* **Adaptive Design**: Fully responsive layout using modern CSS `clamp()` functions, ensuring a great experience on both mobile and desktop.
* **Interactive UI**: Includes score tracking, turn indicators, "thinking" animations for the AI, and win-state highlights.

##  Technologies Used

* **HTML5**: Semantic structure.
* **CSS3**: Custom properties (variables), Flexbox, Grid, and Keyframe animations.
* **JavaScript (Vanilla)**: ES6+ logic without any external libraries or frameworks.
* **Google Fonts**: 'Bebas Neue' for headings and 'DM Mono' for the technical feel.

##  AI Logic: The Minimax Algorithm

The core of the AI is based on a recursive **Minimax algorithm with Alpha-Beta pruning**. 
* It evaluates all possible future moves to ensure the "Computer" player always chooses the most optimal path.
* In **Hard** mode, the AI will never lose; it will either win or force a draw.

##  How to Run

1.  Clone this repository or download the source code.
2.  Open `tictactoe.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  No installation or local server is required!
