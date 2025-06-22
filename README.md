# Hangman-Game-
- Hangman is a classic word-guessing game in which the player attempts to guess a secret word one letter at a time. This Python implementation is a simple command-line version where players have a limited number of incorrect guesses before the game ends. 
- The game provides visual feedback using hangman stages, showing the player's progress and how many tries are left.
- Game Objective
  - Guess the hidden word by suggesting letters. You win if you reveal the entire word before running out of lives. If not, you get "hanged"!

## How to Play
- The program randomly selects a word from a predefined list.
- The user is asked to guess one letter at a time.
- Correct guesses reveal the letter in the word.
- Incorrect guesses reduce the number of remaining chances.
- The game ends when:
  - All letters are guessed correctly (win), or
  - All chances are used (lose)
## Technologies Used
- Language: Python 3
- No external libraries required
- Optional: `random` module for word selection


## Files
- `hangman.py`: The main script to run the Hangman game.
- `words.txt`: A text file containing a list of words for the game.
- `stages.txt`: A text file containing the hangman stages, separated by `###`.

## Project Structure
![image](https://github.com/user-attachments/assets/a5a8ec32-e8da-4e3e-87f1-05253f952f17)

## Steps to Run
###  Clone the Repository
- ````
  git clone https://github.com/CodeCrafter-101/hangman-game.git cd Hangman-Game
  ````
### Run the Game
````
python hangman.py
````
## Features
- Tracks letters guessed and remaining lives
- Displays the current state of the word after each guess
- Handles invalid inputs gracefully
- Simple, clean CLI interface
