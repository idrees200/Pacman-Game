# PACMAN Game Project

## Overview

This project implements a classic arcade game, PACMAN, using C++ with a focus on Object-Oriented Programming (OOP) principles and file handling. The game involves controlling PACMAN through a maze to eat pac-dots while avoiding enemies (MONSTERS). Players can create accounts to save their progress and resume gameplay from where they left off.

## Features

- **Gameplay Mechanics:**
  - **PACMAN Movement:** Controlled by keyboard input (arrow keys).
  - **Pac-Dots:** Collectible items that increase the player's score.
  - **Levels:** Advancement to the next level upon eating all pac-dots in the current level.
  - **Enemies (MONSTERS):** Roaming the maze to catch PACMAN. Contact with MONSTERS ends the game.

- **User Accounts:**
  - **Account Creation:** Players can create accounts with a unique username and password.
  - **File Handling:** Player progress is saved in binary format (dat files). This allows players to resume gameplay from their last session by logging in.

- **Object-Oriented Programming:**
  - **Class Structure:** PACMAN, MONSTERS, and Player are implemented as separate classes.
  - **Encapsulation:** Each class encapsulates its attributes and behaviors.
  - **Inheritance:** Potential use of inheritance for different types of MONSTERS or power-ups.

- **Graphics:**
  - **Visual Appeal:** Utilizes graphics to enhance user experience and make the gameplay more interactive and engaging.
  - **Maze Design:** Creative and intricate maze designs to challenge players.

- **Multiplayer Support:**
  - **Independent Play:** Players can create accounts and maintain separate game progress.
  - **Leaderboards:** Optionally implement a leaderboard to display high scores or achievements.

## Gameplay Flow

1. **Start Screen:**
   - Welcome screen with options to create a new account or log in.

2. **Game Interface:**
   - Display of PACMAN, pac-dots, MONSTERS, and the maze.
   - Score Display: Real-time display of the player's score and current level.

3. **Game Over:**
   - Display when PACMAN is caught by a MONSTER, showing the final score and options to restart or quit.

## Technical Details

- **Programming Language:** C++
- **Libraries:** Graphics libraries for visual effects (optional, based on implementation).
- **File Handling:** Binary files (.dat) for saving player progress.
- **User Interface:** Utilizes console-based or graphical user interface (GUI) for interaction.

## Future Enhancements

- **Power-Ups:** Implement power-ups to enhance PACMAN's abilities or score.
- **Enhanced Graphics:** Utilize advanced graphics libraries for more realistic gameplay.
- **Multiplayer Mode:** Enable real-time multiplayer mode for competitive play.
- **Sound Effects:** Add sound effects to enrich the gaming experience.

## Conclusion

The PACMAN game project combines classic arcade gameplay with modern programming techniques, making it both nostalgic and appealing to players of all ages. It demonstrates proficiency in OOP concepts, file handling, and graphical user interface design, providing a comprehensive learning experience for computer science students.
