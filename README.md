# Alien Invasion Game

A classic arcade-style space shooter game built with Python and Pygame. Players control a spaceship to shoot down invading aliens while avoiding collisions. This project is a great introduction to game development with Pygame and object-oriented programming in Python.

## Features

Player-controlled spaceship that moves left and right

Alien fleet that moves and descends toward the player

Bullets fired by the player to destroy aliens

Scoreboard tracking current score, high score, level, and remaining ships

Multiple levels with increasing difficulty

Start/restart game using the Play button

## Installation
1. Make sure you have Python 3.x installed. You can download it from python.org.
2. Install Pygame
3. Clone this repository
4. Run the game using 'python alien_invasion.py'

## How to Play
- Use the left and right arrow keys to move the ship.
- Press the spacebar to fire bullets.
- Shoot all the aliens before they reach the bottom or collide with your ship.
- The game gets progressively harder as you advance levels.
- Click the Play button to start or restart the game.

## Project Structure
- alien_invasion.py — main game loop and initialization
- settings.py — game settings and configurations
- ship.py — player spaceship class
- alien.py — alien enemy class
- bullet.py — bullet projectile class
- button.py — Play button class
- game_stats.py — tracks game statistics like score and ships left
- scoreboard.py — displays scores and levels on screen
- images/ — folder containing game images like ship and alien
- README.md — this file


## Acknowledgments
Based on concepts from Python Crash Course by Eric Matthes

Pygame library: https://www.pygame.org/

Thanks to the Pygame community for support and tutorials




