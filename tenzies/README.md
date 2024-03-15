# Tenzies Dice Game
Tenzies Dice Game is a simple yet addictive dice game created with React. It provides users with a fun way to roll dice and aim for a winning combination. The game involves rolling ten dice and trying to match their values. Users can strategically choose which dice to hold and which ones to re-roll in pursuit of a winning outcome.

## Features
Users can roll ten dice and attempt to match their values.
Each die can be individually held or released for re-rolling.
The game detects when all dice show the same value, indicating a winning condition.
Players can start a new game after achieving a winning roll.

## Project Structure
The project consists of the following components:

- App.js: 
The main component responsible for managing game state and rendering the game interface.
- Die.js: 
A reusable component representing a single die, handling its display and interaction.
- App.css: 
Stylesheet defining the visual layout and design of the game.

## App.js 

### State Management:
Manages the state of the game, including the values and holding status of each die.
Tracks whether the current roll results in a winning combination.
Handles the logic for rolling dice, holding/unholding dice, and starting a new game.

### Rendering:
Renders the game interface, including the dice grid, roll button, and game information.
Updates the UI dynamically based on the game state and user interactions.

## Die.js

### Props:
Receives props such as value, isHeld, and selectDieOnHold to customize the appearance and behavior of each die.

### State Management:
Manages local state to represent the holding status of the die.

### Rendering:
Renders individual dice elements based on the provided props.
Allows users to click on dice to toggle their holding status.