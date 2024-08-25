# Icy Tower 

## Description

https://drive.google.com/file/d/1iQwX5tztLh6_TyMfzMPc1aL1-s7aK_Rj/view?usp=share_link

This project is a modified clone of the popular game 'Icy Tower', implemented using HTML5 Canvas and JavaScript. It features a player character who must jump from platform to platform, climbing as high as possible while avoiding obstacles and enemies. The game includes various power-ups, different types of platforms, and a scoring system.

## Installation and Requirements

To run this game, you need:
1. A modern web browser (Chrome, Firefox, Safari, or Edge)
2. Visual Studio Code (recommended)
3. Live Server extension for Visual Studio Code

### Steps to run the game:
1. Clone this repository to your local machine
   - Make sure to clone the entire project, including the `photos/` folder
   - The `photos/` folder contains all the necessary image assets for the game
2. Open the project folder in Visual Studio Code
3. Install the Live Server extension if you haven't already
4. Right-click on the `index.html` file in VS Code
5. Select "Open with Live Server"
6. The game should now open in your default web browser

**Important Note:** Ensure that the `photos/` folder is present in your local project directory after cloning. This folder contains crucial image assets required for the game to display correctly.

## How It Works
- Use arrow keys to move the player left and right
- Press the up arrow or spacebar to jump
- Climb as high as you can by jumping from platform to platform
- Avoid falling off the bottom of the screen
- Collect power-ups and avoid enemies
- Your score increases as you climb higher

## Project Structure
- `index.html`: The main HTML file for the game
  - Contains the game's HTML structure
  - Includes embedded JavaScript code that controls the game logic
- `photos/`: Directory containing image assets used in the game
  - This folder includes all the graphical elements such as the player character, platforms, background, enemies, and power-ups

## Features
- Score tracking system
- Falling platforms (if stood on for more than 3 seconds)
- Numbered platforms every 10 levels
- Two types of enemies: stationary and moving
- Power-up stars for temporary invincibility
- Game over screen with "Play Again" option
- Leaderboard showing top 10 scores
- Various platform types including wider platforms and moving platforms
- Custom graphics for background, player, and platforms

## Technologies Used
- HTML5
- Canvas API for rendering graphics
- JavaScript (embedded in HTML file)
  - Used for game logic, including:
    - Player movement and physics
    - Platform generation and behavior
    - Enemy AI
    - Collision detection
    - Score tracking
    - Game state management
- CSS (minimal, embedded in HTML file)
- Local Storage for saving high scores



