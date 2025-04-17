
# 🚀 Space Invaders Game in C++ with raylib

Welcome to our version of **Space Invaders**, developed using **C++** and the **raylib** library! This project was part of our journey into game development, focusing on object-oriented programming, game loops, and 2D graphics programming.

---

## 🧠 Learning Goals

This project helped us explore and implement:

- The structure and logic of 2D games  
- Real-time user input and event handling  
- Collision detection and response  
- Organizing game assets (images, sounds, fonts)  
- Writing clean, modular, object-oriented C++ code

---

## 🎮 Game Summary

A simple recreation of the classic **Space Invaders**:

- Control a spaceship at the bottom of the screen  
- Shoot projectiles to destroy descending alien invaders  
- Game ends when enemies reach the bottom or you lose all lives  
- Score increases with each enemy destroyed  
- Limited lives system adds challenge

---

## 📸 Screenshots & Preview

Here’s a glimpse of our *Space Invaders* game in action and how it looks for beginners diving in with C++ and raylib:

### In-Game Screenshot
![Space Invaders Gameplay](IMG-20250417-WA0000.jpg)

### Tutorial Artwork
![Space Invaders for Beginners](IMG-20250417-WA0001.jpg)

---

## 📖 How to Play

- **← / → Arrow Keys**: Move the spaceship  
- **Spacebar**: Fire bullets  
- **Esc**: Exit the game

### 🎯 Objective

Destroy all invaders before they reach your ship or you run out of lives!

---

## ⚙️ How to Run the Game

### ✅ Prerequisites

- A working **C++ compiler** (e.g., `g++`)  
- **raylib** library installed  
- **Visual Studio Code** (recommended)

### 🔧 Installation Steps

```bash
# Clone the repository
git clone https://github.com/educ8s/CPP-Space-Invaders-Game-with-raylib.git

# Navigate into the project directory
cd CPP-Space-Invaders-Game-with-raylib
```

### ▶️ Running the Game

Open `main.code-workspace` in VS Code. Press F5 or compile and run from the terminal.  
Ensure raylib is correctly set up and linked.

### 📁 Project Structure

```
CPP-Space-Invaders-Game-with-raylib/
├── src/                 # C++ source files
├── Graphics/            # Image assets
├── Sounds/              # Sound effects
├── Font/                # Custom fonts
├── lib/                 # External libraries
├── .vscode/             # VS Code configuration
├── Makefile             # Build instructions
├── main.code-workspace  # VS Code workspace file
```

---

## 🔄 Game Loop Analysis

### *1. Input Handling*
- Captures real-time keyboard input (left/right/space).
- Ensures responsive controls.

### *2. Update Phase*
- Player's position updates based on input.
- Bullets move upward; inactive bullets are removed.
- Enemies descend; game ends if they reach the bottom.
- Collision detection runs between bullets and enemies.

### *3. Render Phase*
- Draws player, bullets, and enemies.
- Displays lives and score using raylib’s text rendering.
- Handles game-over or win states.

---

## 🧩 Concepts Implemented

- Real-time game loop for updates and rendering  
- Classes for player, bullets, and enemies  
- Arrays/vectors for managing projectiles and enemies  
- Collision detection (bullet-enemy, enemy-player)  
- Score and life UI  
- Sound effects for interactions

---

## 💡 Development Experience

This project gave us practical exposure to:

- Structuring interactive real-time applications  
- Debugging and optimizing C++ code  
- Using raylib for 2D graphics and audio  
- Designing simple but fun gameplay  
- Asset management and polishing

---

## 🔮 Future Improvements

- Levels with increasing difficulty  
- Power-ups and special weapons  
- High score tracking  
- Background music and animations  
- Main menu and pause/resume features

---

## 📈 Planned Future Enhancements

- *Multiple Difficulty Levels*: Introduce a difficulty scaling system, where the game speed and the number of enemies increase progressively as players advance.  
- *New Enemy Types*: Implement new alien invader types with different behaviors (e.g., faster, more aggressive, or with special abilities).  
- *Power-ups*: Add power-ups such as shield boosts, faster shooting, or bombs to eliminate multiple enemies at once.  
- *Leaderboard System*: Add an online leaderboard to track high scores and encourage replayability.  
- *Game Modes*: Introduce additional game modes, like time trials or survival mode.  
- *Multiplayer Support*: Implement a cooperative multiplayer mode where two players can team up to fight the invaders.

---

## 👨‍💻 Contributors

**Team: Code Mavericks**  
- Tirth Solanki  
- Darpan Sherathiya  
- Deep Shobhashana  
- Shaurya Pratap Singh Shekhawat  

🛠️ Open for Contributors! Feel free to fork and improve the game.

---
