# 2D Game Portfolio

The project is a 2D game built using the Kaboom.js library, featuring interactive exploration and dialogue mechanics.

## Table of Contents

1. [Description](#description)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Contributing](#contributing)


## Description

This project utilizes Kaboom.js for creating a 2D game environment. It includes features such as:
- Dynamic loading and handling of sprites and tile maps.
- Player movement and interaction with boundaries and objects based on collision detection.
- Dialogue system that displays text sequentially and allows interaction via mouse clicks or key presses.
- Responsive camera scaling based on the game window's aspect ratio.

The game environment includes various interactive elements like PCs, TVs, beds, and more, each triggering dialogue interactions when the player collides with them. Movement of the player is facilitated through mouse clicks or keyboard arrow keys, with animations corresponding to different directions.

## Technologies Used

- **Kaboom.js**: A JavaScript library for creating games and interactive simulations.
- **JavaScript**: The primary programming language used for game logic and interactions.


## Project Structure

```
project-root/
│
├── node_modules/        # Dependencies installed by npm
├── public/              # Public assets like images, fonts, etc.
│   ├── map.json            # Map data like boundries, etc
│   ├── map.png             # Map png
│   ├── monogram.ttf        # TrueType font file
├── └── spritesheet.png     # Spritesheet
├── src/                 # Source code files
│   ├── constants.js       # Constants used in the project
│   ├── kaboomCtx.js       # File for handling Kaboom context
│   ├── main.js            # Main entry point of the application
│   └── utils.js           # Utility functions
├── package-lock.json    # Dependency lock file
├── package.json         # Project manifest
└──  vite.config.js      # Vite configuration file
```

## Installation

To install and run the project locally:

1. Clone the repository.
2. Install dependencies using npm.
3. Start the development server.
4. Open the game in a web browser to interact with the environment.

## Contributing

Contributions to the project are welcome. To contribute:
- Fork the repository.
- Create a new branch for your feature or fix.
- Make your changes and submit a pull request.
