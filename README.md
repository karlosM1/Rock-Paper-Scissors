# Rock-Paper-Scissors Game

## Overview
This is a simple Rock Paper Scissors game implemented in HTML, CSS, and JavaScript. The game allows players to select their move (rock, paper, or scissors) and then compares it against a randomly chosen move by the computer. The score is tracked and can be reset by the user.

## Files
- index.html: The main HTML file that contains the structure of the game.
- styles/rpc.css: The CSS file that styles the game.
- scripts/rpc.js: The JavaScript file that contains the game logic.
## HTML Structure
The HTML file contains the following key elements:
- A title for the game.
- Buttons for selecting rock, paper, or scissors, each with an associated image.
- Paragraph elements to display the result of the game, the moves made, and the current score.
- A reset button to clear the score.
## Key Elements
- Buttons: Each button calls the playGame function with the respective move ('rock', 'paper', or 'scissors') when clicked.
- Result Paragraph (.js-result): Displays the result of the current game.
- Moves Paragraph (.js-moves): Shows the moves made by both the player and the computer.
- Score Paragraph (.js-score): Displays the current score.
- Reset Button: Resets the score to 0 for wins, losses, and ties, and removes the score from local storage.
## JavaScript Functionality
The JavaScript file rpc.js should contain the logic to:
- Handle the playGame function to determine the winner based on the player's and computer's moves.
- Update the result, moves, and score elements accordingly.
- Persist the score using localStorage so that it remains across page reloads.
- Reset the score when the reset button is clicked.
