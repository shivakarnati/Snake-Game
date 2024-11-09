# Snake Game 🐍

This repository contains a simple **Snake Game** developed in Java! The classic Snake Game features a snake that grows longer as it consumes food. The game ends when the snake collides with the wall or itself. This project uses three main components: **Game Panel**, **Action Listener**, and **Keyboard Adapter**.

## Table of Contents

- [About the Game](#about-the-game)
- [Game Components](#game-components)
  - [1. Game Panel](#1-game-panel)
  - [2. Action Listener](#2-action-listener)
  - [3. Keyboard Adapter](#3-keyboard-adapter)
- [Gameplay Instructions](#gameplay-instructions)

---

## About the Game

The **Snake Game** is a fun and interactive game where you control a snake on the screen, trying to eat as much food as possible without crashing into the walls or itself. With each piece of food the snake eats, it grows longer, increasing the difficulty as you try to navigate through the game area.

## Game Components

This Java game is built using three main components:

### 1. Game Panel

The **Game Panel** is responsible for rendering the game graphics, such as the snake, food, and background. It also manages the game’s state, like starting, pausing, and ending the game. The Game Panel is updated in real-time to ensure smooth gameplay and visual updates.

### 2. Action Listener

The **Action Listener** is used to keep the game running in a loop, updating the game’s state at regular intervals. It checks for events like the snake eating food, or collisions with the walls or itself, and triggers the appropriate responses, such as increasing the score or ending the game.

### 3. Keyboard Adapter

The **Keyboard Adapter** is used to detect and respond to keyboard inputs from the player. It allows the player to control the snake's direction (up, down, left, right) by listening for arrow key presses. The adapter ensures smooth and responsive gameplay by quickly updating the snake’s direction based on the player’s input.

## Gameplay Instructions

- Use the **arrow keys** to control the direction of the snake.
- Guide the snake to the **food** to score points and grow longer.
- **Avoid collisions** with the walls or the snake’s own body, or the game will end.
- Try to achieve the highest score possible by consuming as much food as you can!
