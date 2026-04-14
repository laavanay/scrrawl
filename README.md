# Scrrawl 🖌️

Welcome to **Scrrawl**, a real-time multiplayer drawing and guessing game! Invite your friends, unleash your inner artist, and guess what others are drawing to earn points.

## ✨ Features
- **Real-Time Gameplay**: Enjoy seamless communication powered by Node.js and Socket.io.
- **Customizable Rooms**: Tweak your game's settings using the built-in admin chat commands.
- **Voting System**: Let everyone decide if a drawing is a masterpiece 👍 or a disaster 👎.

## 🚀 Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine. All dependencies can be installed easily.

```bash
git clone https://github.com/laavanay/scrrawl.git
cd scrrawl
npm install
```

### Running the Server
To start the game server locally, simply run:
```bash
node server.js
```
The game will be available at [http://localhost:3000](http://localhost:3000). To play with friends over the internet, you can use port forwarding or a service like ngrok.

## 🛠️ Admin Commands
If you have the admin password, you can control the server directly from the chat box!
Type `//admin {password} {command} [args]`

### Available Commands:
- `kickall`: Kicks all players and restarts the game
- `kick {username}`: Kicks a specific player
- `givePoints {username} {value}`: Give a player some extra points
- `setdrawtime {seconds}`: Change the drawing timer
- `setchoosetime {seconds}`: Change the word-selection timer
- `restart`: Restarts the ongoing game

## 📝 License
This project is created and maintained by **laavanay**. Feel free to star the repository if you enjoyed playing!
