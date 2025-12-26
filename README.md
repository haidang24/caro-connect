# Caro Connect

The online multiplayer game Caro (Gomoku) is built using JavaScript, Socket.IO, and Express.

## How to install

1. Install Node.js (version 14.x or later) from [nodejs.org](https://nodejs.org/)
2. Clone or download this repository
3. Open Terminal/Command Prompt in your project directory
4. Install the dependencies:

```bash
npm install
```

## How to run

1. Start the server:
   
```bash
npm start
```

2. Open your browser and go to `http://localhost:3000`
3. Create a new room by entering a name and leaving the room code blank
4. Share the created room code with your friends
5. The second player enters their name and room code to join

## How to play

- The first player will be marked with an X, the second player with an O.
- The goal is to form 5 consecutive pieces horizontally, vertically, or diagonally.
- Players take turns playing on the empty squares on the board.
- The first player to achieve 5 consecutive pieces wins.
- The winner receives 1 point.

## Features

- Real-time multiplayer game
- Create and join private game rooms
- Change board size (10x10, 15x15, 20x20)
- Scoreboard tracking
- Last move highlighting effect
