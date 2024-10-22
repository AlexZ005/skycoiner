# Multiplayer Coin Collector Game

A collaborative 2D multiplayer game implemented using HTML5, CSS3, and JavaScript with real-time communication capabilities through WebSockets.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Gameplay](#gameplay)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Contributing](#contributing)
- [Screenshots](#screenshots)
- [License](#license)

## Features
- Real-time player movement synchronization.
- Coin collection with score tracking for two players.
- Simple audio feedback on coin collection.
- Responsive design suitable for various screen sizes.

## Gameplay
1. Start the game and share your room code with another player to invite them to join.
2. Use arrow keys or WASD controls to move your character around the game area.
3. Collect coins scattered across the game area to increase your score.
4. Real-time updates ensure that both players see the same game state.

## Technologies Used
- **HTML5** for structure and content.
- **CSS3** for styling and animation.
- **JavaScript** for logic, event handling, and real-time communication through WebSockets or similar protocols.
- **WebSockets** for peer-to-peer connection establishment and data transmission between players.

## Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge).
- Node.js with npm/yarn installed to run the backend server if necessary. (Optional: If not using a static file server.)

### Installation Steps
1. Clone this repository onto your local machine:
   ```bash
   git clone git@github.com:AlexZ005/skycoiner.git
   ```
1. Navigate into the project directory.
For development purposes, you may need to start a local web server to serve the game files. Use a simple HTTP server like live-server (npm package) if no backend is involved:
   ```bash
   npm install -g live-server # Install live-server globally
   live-server .            # Start the server in this directory
   ```
Alternatively just move index.html into the browser new tab.

## Screenshots

The screenshots of a game can be found in [Releases](https://github.com/AlexZ005/skycoiner/releases) page.

## Contributing
Contributions are welcome! Please submit a pull request for any improvements, bug fixes, new features, etc. Be sure to follow existing code styles and include tests when appropriate.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

