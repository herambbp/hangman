# Hangman Game

This is a simple implementation of the classic game Hangman. The program randomly selects a word from a predefined list, and the player must guess letters to uncover the word before running out of lives.

## How to Play

1. Run the script to start the game.
2. The program will display a series of underscores representing the hidden word.
3. Guess a letter by entering it through the console. The letter should be in lowercase.
4. If the letter is correct and present in the word, it will be revealed in the corresponding positions.
5. If the letter is incorrect, you will lose a life.
6. The game ends when either you uncover the entire word or you run out of lives.

## Prerequisites

Make sure you have the following files in the same directory as the script:

- `hangman_art.py`: Contains ASCII art used for visual representation during the game.
- `hangman_words.py`: Contains a list of words that the program can choose from.

## Usage

```python
python hangman.py
```

## Example Output

```
  _   _                                               
 | | | |                                              
 | |_| | __ _ _ __   __ _ _ __ ___   __ _ _ __         
 |  _  |/ _` | '_ \ / _` | '_ ` _ \ / _` | '_ \        
 | | | | (_| | | | | (_| | | | | | | (_| | | | |       
 |_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|       
                    __/ |                              
                   |___/                               

Pssst, the solution is pineapple.
_ _ _ _ _ _ _ _ _

Guess a letter: a
_ a _ _ _ _ _ _ _

Guess a letter: e
You guessed e, that's not in the word. You lose a life.
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
_ a _ _ _ _ _ _ _

Guess a letter: i
_ a _ _ _ _ _ _ _

Guess a letter: n
_ a n _ _ _ _ _ _

Guess a letter: p
p a n _ _ _ _ _ _

Guess a letter: l
p a n _ _ _ _ l _

Guess a letter: e
p a n _ _ _ _ l e

Guess a letter: i
You've already guessed i
p a n _ _ _ _ l e

Guess a letter: r
p a n _ _ _ _ l e

Guess a letter: c
p a n _ _ _ _ l e

Guess a letter: o
p a n _ _ _ _ l e

Guess a letter: t
p a n t _ _ _ l e

Guess a letter: s
p a n t s _ _ l e

Guess a letter: q
You guessed q, that's not in the word. You lose a life.
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
p a n t s _ l e

Guess a letter: h
p a n t s h l e

You win.
```

Have fun playing Hangman!
