
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable Hangman game in Python using strings, loops, conditionals, and user input. By the end of this assignment, you will create a full game loop that tracks guesses and clearly reports win or loss outcomes.

## 📝 Tasks

### 🛠️	Set Up the Game Word and Display

#### Description
Create the starting game state for Hangman. Define a list of possible words, randomly choose one word, and display the hidden word to the player using underscores for unguessed letters.

#### Requirements
Completed program should:

- Create a predefined list with at least 5 possible words.
- Randomly select one word from the list when the game starts.
- Display the current progress in underscore format (for example: `_ _ _ _`).
- Update the displayed word after each valid guess.


### 🛠️	Implement Guessing Logic and Win/Lose Conditions

#### Description
Build the main gameplay loop. Accept one letter guess at a time, track incorrect guesses, prevent repeated input issues, and stop the game when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Accept user input as a single letter guess each turn.
- Track and display remaining incorrect guesses.
- End the game with a win message when all letters are guessed.
- End the game with a lose message when attempts are exhausted.
- Show the correct word when the player loses.

Example interaction:

```text
Word: _ _ _ _
Guess a letter: a
Incorrect guesses remaining: 5

Word: _ a _ _
Guess a letter: t
Incorrect guesses remaining: 4
```
