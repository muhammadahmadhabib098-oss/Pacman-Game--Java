# Pacman-Game--Java
This is console base JAVA Pacman Game.
🎮 PacMan Console Game (Java)
This is a simple console-based PacMan game implemented in Java using Object-Oriented Programming (OOP) concepts. The game runs on a 5×5 grid, where the player controls PacMan, collects food, and avoids a ghost.
🚀 Features
🟡 PacMan movement using keyboard input (W, A, S, D)
👻 Random ghost movement
🍎 Food spawning and respawning
📊 Score tracking system
🧠 Boundary checking for valid moves
💀 Game over when PacMan is caught by the ghost
🧱 Game Structure (Classes)
The project is divided into the following classes:
1. PacMan
Handles player position and movement
Tracks score
Methods:
move()
increaseScore()
Getters for position and score
2. GameBoard
Represents a 5×5 grid
Displays game state in console
Validates movement within boundaries
3. Ghost
Moves randomly on the board
Causes game over on collision with PacMan
4. Food
Represents collectible item
Respawns randomly after being eaten
5. PacManGame (Main Class)
Controls game loop
Handles user input
Updates game state
🎮 How to Play
Use the following keys to move PacMan:
Key
Direction
W
Up
S
Down
A
Left
D
Right
Objective:
Eat food (.) to gain points
Avoid the ghost (G)
Survive as long as possible
- - - - -
- P - - -
- - . - -
- - - G -
- - - - -

Move (W/A/S/D):
. Compile the code
Bash
javac PacManGame.java
2. Run the program
Bash
java PacManGame
## Authror:
M. Ahamd Habib
