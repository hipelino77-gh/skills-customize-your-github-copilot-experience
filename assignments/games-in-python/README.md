# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game in Python that gives players a limited number of chances to uncover a hidden word. Practice using strings, loops, conditionals, random selection, and user input.

## 📝 Tasks

### 🛠️ Create the guessing game

#### Description
Create a Hangman game that randomly chooses a word from a predefined list and lets the player guess its letters.

#### Requirements
Completed program should:

- Select one word at random from a list of words.
- Show each letter in the word as a blank, such as `_ _ _ _`, and reveal correctly guessed letters in their positions.
- Accept guesses from the player and update the displayed word after each guess.


### 🛠️ Track attempts and finish the game

#### Description
Track incorrect guesses and end the game when the player either reveals the whole word or runs out of attempts.

#### Requirements
Completed program should:

- Track and display how many incorrect guesses the player has remaining.
- Reduce the remaining attempts when the player guesses an incorrect letter.
- Display a win message when the player guesses the whole word.
- Display a lose message and reveal the word when the player runs out of attempts.
