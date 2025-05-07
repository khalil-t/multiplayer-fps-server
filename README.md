# Multiplayer FPS Server with Socket.io

This is a simple multiplayer FPS server using **Socket.io** to handle real-time player connections, movements, shooting, and disconnections. Players can move around the game area, shoot at other players, and get notified when another player dies or disconnects.

---

## 🚀 Features

- **Player Connections:** Players can connect to the game and are assigned unique socket IDs.
- **Player Movement:** Players can move in the game world, and their movements are broadcasted to all other players.
- **Player Shooting:** Players can shoot at each other, reducing the target's health points (HP). When a player's HP reaches 0, they are considered "dead."
- **Player Disconnections:** When a player disconnects, their information is removed from the game and broadcasted to all other players.

---

## 📦 Requirements

- Node.js
- Express
- Socket.io

---

## 📂 Folder Structure

```txt
your-project/
├── server.js               # Main server file with game logic
├── package.json            # Project dependencies and scripts
└── README.md               # Project documentation
