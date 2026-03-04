
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Initialize the game by setting up a word list and randomly selecting a word for the player to guess.

#### Requirements
Completed program should:

- Define a list of words for the game
- Randomly select a word from the list
- Initialize tracking variables for incorrect guesses and discovered letters
- Display the game state with blank spaces (__ __ format)


### 🛠️ Letter Guessing and Game Logic

#### Description
Implement the main game loop that accepts letter guesses and updates the game state accordingly.

#### Requirements
Completed program should:

- Accept letter guesses from the user
- Show current progress with revealed letters and blanks
- Track incorrect guesses remaining
- Validate input and handle duplicate guesses
- End the game when the word is guessed or attempts are exhausted


### 🛠️ Win/Lose Conditions and Feedback

#### Description
Implement game-ending logic and provide appropriate win/lose messages.

#### Requirements
Completed program should:

- Display a win message when the word is completely guessed
- Display a lose message when attempts are exhausted
- Reveal the secret word at the end of the game
- Provide clear feedback on game status and remaining attempts
- Implement proper game flow and replay functionality
