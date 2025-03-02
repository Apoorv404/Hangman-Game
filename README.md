# Hangman-Game

This is a simple Hangman game implemented in Python. The objective of the game is to guess the hidden word by suggesting letters within a certain number of guesses.

## Concepts Covered

- Random number generation
- String manipulation
- User input handling
- Looping and conditional statements

## Files

- `main.py`: The main script that runs the Hangman game.
- `hangman_words.py`: Contains the list of words used in the game.
- `hangman_art.py`: Contains the ASCII art for the game stages and the game logo.
- `README.md`: This file.
- `LICENSE`: The license for the project.

## How to Play

1. Run the `main.py` script.
2. The game will randomly select a word from the word list.
3. You will be prompted to guess a letter.
4. If the guessed letter is in the word, it will be revealed in its correct position(s).
5. If the guessed letter is not in the word, you lose a life.
6. The game continues until you either guess the word correctly or run out of lives.

## Example

```sh
$ python main.py
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/                       
Word to guess: _______
****************************<???>/6 LIVES LEFT****************************
Guess a letter: a
Word to guess: a_____
****************************<???>/6 LIVES LEFT****************************
Guess a letter: b
You guessed b, that's not in the word. You lose a life.
Word to guess: a_____
  +---+
  |   |
  O   |
 /|\  |
 /    |
      |
=========