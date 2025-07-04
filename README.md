# 🕹️ Super Smash Homies

**Super Smash Homies** is a feature-rich 2D multiplayer platformer built in **Python** using **Pygame**. Developed as a class project, SSH is a split-screen brawler where up to four players battle it out on dynamic maps with real-time collisions, unique abilities, and customizable characters.

---

## 🎮 Key Features

- **🧍 Local Multiplayer:** Up to 4 players can join the fun using PS4, Xbox controllers, or keyboard.
- **🔀 Split-Screen Support:** Each player gets their own camera view in dynamic split-screen mode.
- **🎨 Fully Customizable:** Swap in different characters, maps, music, and sounds with ease.
- **💣 Dynamic Gameplay:** Battle friends while dodging enemies and environmental hazards.
- **📐 Built with ECS:** Uses an **Entity-Component-System** architecture for scalable game logic.
- **💥 Polished UX:** Smooth transitions, win/lose animations, and scene management for pro feel.

---

## 🧠 What I Learned

- Collision detection & character physics  
- ECS-based architecture for scalability  
- Split-screen camera logic for multiple players  
- Real-time input handling across controllers  
- Audio management and asset structuring  
- How to balance fun, performance, and clean code

---

## 🗂️ Project Structure

SSH/
└── src/
├── assets/ # Game images and backgrounds
├── music/ # Background tracks
├── sounds/ # SFX (jumps, hits, etc.)
├── UI.py # User interface rendering
├── engine.py # Core game loop and ECS logic
├── globals.py # Shared constants and variables
├── inputstream.py # Input management for keyboard/controllers
├── level.py # Level layout and objects
├── main.py # Entry point
├── scene.py # Scene transitions (win/lose, menu)
├── soundmanager.py # Music/SFX playback
└── utils.py # Helper functions/utilities

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Pygame

### Installation

```bash
pip install pygame

cd Super-Smash-Homies/src
python main.py

