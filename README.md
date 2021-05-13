# Hangman Game

## Introduction

This version of hangman was made by Louis Giët.\
Student number: 01912470.

## Features

### How to play
You can choose a letter by either:
- clicking on a buttons on the screen
- pressing a key on your keyboard
- using guessLetter(letter: str) in the console

\
The game is fully playable in the console.
 ```JavaScript
 // Example
gameState;
{mistakes: 2, length: 5, template: "_A___", lockedLetters: {A: [1]}}

guessLetter("B");

gameState;
{mistakes: 3, length: 5, template: "_A___", lockedLetters: {A: [1]}}

restart();

gameState; // restart reset the gameState Object
{mistakes: 0, length: 10, template: "__________", lockedLetters: {}}

``` 

### Settings
You can change the keyboard layout to:
- Azerty
- Qwerty
- Alphabetical

\
You can change the game mode to:
- Deceptive: The game picks a new word to avoid a letter being correct until it is out of options.
- Easy: The normal hangman mode, where where one word gets chosen
- Baby: Deceptive hangman with infinite tries

### Extra
Your wins and losses get tracked in the settings tab.
