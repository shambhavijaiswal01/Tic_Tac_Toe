# Tic_Tac_Toe
A fun and interactive Tic Tac Toe game built with HTML, CSS, and JavaScript. This game features smooth animations, sound effects, and a visually appealing design. Play against a friend and see who can win or if it ends in a draw!
Key Features
Interactive 3x3 Grid: Players take turns to mark spaces with "X" or "O". The game automatically checks for a winner or draw after every move.

Visual Feedback:

Winning combinations are highlighted with a stylish line and an "excited" GIF.

A "draw" GIF appears when the game ends in a tie.

Sound Effects:

Background music plays during the game.

Interactive sounds for turn changes, winning, and drawing.

Responsive Design: The game board and layout adapt to different screen sizes for a seamless experience on desktop and mobile.

Reset Button: After the game ends, click "Reset" to start a new game.

Technologies Used
HTML: Structuring the page, game grid, buttons, and instructions.

CSS: Styling the game, including background gradients, layout, hover effects, and responsiveness.

JavaScript: Game logic for player turns, win detection, audio, and animations.

How to Play
Click on any empty cell in the 3x3 grid to place your mark ("X" or "O").

Take turns with your opponent.

The first player to get three of their marks in a row, column, or diagonal wins.

If all cells are filled and there is no winner, the game ends in a draw.

Click the "Reset" button to start a new game.

Setup Instructions
To play the game locally:

Clone this repository to your local machine:

bash
Copy
Edit
git clone https://github.com/your-username/tic-tac-toe.git
Open the index.html file in your browser to start playing.

File Structure
graphql
Copy
Edit
/tic-tac-toe
|-- index.html      # HTML structure for the game
|-- style.css       # CSS for styling the game
|-- script.js       # JavaScript file for game logic
|-- music.mp3       # Background music file
|-- ting.mp3        # Sound for a move
|-- gameover.mp3    # Sound for game over
|-- draw.mp3        # Sound for draw
|-- excited.gif     # GIF for winning animation
|-- draw.gif        # GIF for draw animation
