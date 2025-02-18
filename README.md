# Hangman Game

## Description
The **Hangman Game** is a classic word-guessing game implemented in Java using the Swing framework for a graphical interface. The game randomly selects a word from a file, and the player must guess it letter by letter before running out of lives.

## Features

### Word Selection
- Reads a list of words from an external text file (`words.txt`).
- Randomly chooses a word for each game session.

### Game Mechanics
- Displays the hidden word with underscores (`_`) representing unguessed letters.
- Allows players to guess individual letters.
- Supports guessing the entire word.

### Correct Guess
- Reveals the guessed letter in all matching positions.
- Plays a correct sound effect.

### Incorrect Guess
- Deducts a life (heart icon).
- Draws part of the hangman figure.
- Plays an incorrect sound effect.

### Game State
- Tracks remaining lives (initially 6 hearts).
- Displays used letters.
- Provides a graphical hangman drawing based on the number of mistakes.
- Notifies the player of a win or loss.
- Offers a restart option after the game ends.

## Requirements
- **Java Development Kit (JDK)** (tested on Java 8+)
- **words.txt** file containing at least three different words.
- **sounds/** directory with audio files (`background.wav`, `correct.wav`, `wrong.wav`, `winner.wav`, `loser.wav`).

## How to Run
1. Compile the Java files:
   ```sh
   javac Index.java HangMan.java
   ```
2. Run the game:
   ```sh
   java Index
   ```

## Files Structure
```
Hangman/
│-- Index.java            # Main entry point
│-- HangMan.java          # Main game logic
│-- words.txt             # List of words for random selection
│-- sounds/               # Sound effects folder
│   │-- background.wav
│   │-- correct.wav
│   │-- wrong.wav
│   │-- winner.wav
│   │-- loser.wav
│-- README.txt            # Documentation (this file)
```

## Challenges Encountered
As a first-year student (level B1 in Java), some difficulties included:
- **Working with files**: Reading words from a file and handling errors properly.
- **Java Swing UI**: Designing a responsive user interface with panels and buttons.
- **Game logic**: Managing correct and incorrect guesses efficiently.
- **Sound integration**: Implementing background music and sound effects for better engagement.

## Possible Improvements
- Add a difficulty level selection.
- Implement a leaderboard to track scores.
- Enhance the UI with better graphics and animations.

This project was a great learning experience in Java programming, GUI development, and file handling. 🚀

