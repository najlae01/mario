# Super Mario - CS50 Version

## Introduction

This is a simplified version of the classic game "Super Mario" developed as part of the CS50 Introduction to Game Development course. In this game, players control Mario as he navigates through various levels, avoiding obstacles, defeating enemies, and collecting coins to reach the end goal.

![mario](https://github.com/najlae01/mario/assets/88176530/e468f4f0-7650-4d96-8872-474f64aa8406)

## Features

- Side-scrolling platformer gameplay.
- Player movement and jumping mechanics.
- Basic enemy AI with collision detection.
- Level generation with random obstacles and platforms.
- Collectible coins and power-ups.

## Additional Features (from Game Dev Specifications)

1. **Safe Player Spawning**: The player is always spawned above solid ground. This ensures that the player starts the level safely and does not fall upon spawning.

2. **Key and Lock Mechanic**: Generated random-colored key and lock block that unlocks when the player collides with it. The goal post should spawn at the end of the level if the locked block is collected.

3. **Dynamic Level Length**: When the player reaches the goal post, the level is regenerated, the player is spawned at the beginning again, and the level is a little longer than before.

## Controls

- Arrow keys: Move Mario left or right.
- Spacebar: Jump.

## Installation

To run the game, ensure you have Love2D framework installed on your system. You can download Love2D from [the official website](https://love2d.org/).

Clone this repository to your local machine:

```
git clone https://github.com/najlae01/mario
```

## Usage

Navigate to the project directory and run the game with Love2D:

```
cd mario
```
```
love .
```

## Credits

- Developed with Love2D (Lua) as part of the CS50 Introduction to Game Development course.
- Game development specifications and guidance provided by CS50 team.
