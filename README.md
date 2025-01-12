# Hangman Game Project

## Overview
The Hangman game is a classic word-guessing game implemented in Python. Players attempt to guess a randomly selected word, one letter at a time, while trying to avoid running out of lives. The game provides visual feedback using text-based art, simulating a hangman being drawn with each incorrect guess.

## Features
- **Random Word Selection:** The game randomly chooses a word from a predefined list (`hangman_words.py`).
- **Visual Representation:** A series of hangman stages (`hangman_art.py`) represent the progress of the game.
- **Life System:** Players start with 6 lives, losing one for each incorrect guess.
- **Win/Loss Conditions:** The game ends when the player either guesses the word correctly or runs out of lives.
- **Input Handling:** The game handles repeated guesses and provides feedback for already guessed letters.

## How It Works
1. A random word is selected, and its length is represented by underscores.
2. The player guesses a letter. 
3. If the guess is correct, the letter reveals itself in the word.
4. If the guess is incorrect, a life is deducted and the hangman drawing progresses.
5. The game continues until the player guesses the word or runs out of lives.

## Project Structure
- `hangman.py`: Main game logic.
- `hangman_words.py`: Contains the word list for random selection.
- `hangman_art.py`: Contains the hangman stages and game logo.

## Skills Used
- Python basics (`if` statements, loops, functions)
- Random module usage
- String manipulation
- User input handling
- Modular programming

## How to Run
1. Ensure Python is installed.
2. Run the `hangman.py` file.
3. Follow the on-screen instructions to guess the word.

**Enjoy the game and test your word-guessing skills!**

