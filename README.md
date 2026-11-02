# 🎲 THE CURSED BOARD — 3D Horror Snakes & Ladders

A dark, atmospheric 3D horror adaptation of the classic **Snakes & Ladders** game, built with **Three.js**, **Web Audio API**, and **Tailwind CSS**. 

Set upon an ancient stone altar within a foggy midnight forest, players take turns casting the cursed bone die to break the forest ritual by reaching **Cell 100** by exact roll.

---

## 🎮 Play Online / Live Demo

You can play directly in your browser without any installation:
👉 **[Play The Cursed Board Live](https://kishukrgupta.github.io/the-cursed-board/)**

---

## ✨ Features

- **🕯️ Immersive Gothic 3D World:** Built entirely in Three.js with soft shadows, atmospheric volumetric fog, spore particles, flickering sacrificial brazier flames, and twisted forest trees.
- **🐍 8 Realistic Procedural Serpents:** Dynamic coiled 3D serpents with animated jaws, fangs, and slithering tongues that strike and drag victims down to their tails.
- **🪜 8 Weathered Wooden Ladders:** Realistic wooden rungs and scaffolds that players climb toward salvation.
- **🔊 Procedural Horror Sound Engine:** 100% self-contained Web Audio API synthesizer generating ambient dark drones, bone dice clatters, stone footsteps, snake hisses/strikes, and eerie victory chords. Zero external audio files required!
- **🎲 3D Bone Dice Physics:** Fully animated 3D die with realistic tumble and bounce mechanics.
- **👥 Flexible Player Modes:**
  - **Solo (1P):** Journey alone across the altar.
  - **1P vs AI Spirit:** Face an autonomous cursed spirit opponent.
  - **2P, 3P, & 4P Local Ritual:** Pass-and-play multiplayer on a single device.
  - **Multi-Tab Sync:** Synchronize dice rolls and board state across multiple browser tabs using room codes.
- **🎥 Dynamic Camera Controls:** Free orbit rotation and zoom, plus quick presets for **Isometric**, **Top-Down**, and **Follow Piece**.

---

## 📜 Board Rules & Legend

* **Board Layout:** 10x10 Zigzag path from Cell 1 (bottom-left) to Cell 100 (top-left).
* **Movement:** Cast the 6-sided bone die (1–6) to advance your relic piece.
* **Exact Finish:** You must roll the exact number of steps required to reach Cell 100. Over-rolling forfeits your movement for that turn.
* **Serpents (Head ➔ Tail):**
  - Abyssal Viper: 98 ➔ 79
  - Rotscale Python: 95 ➔ 75
  - Void Cobra: 93 ➔ 73
  - Constrictor: 87 ➔ 24
  - Marsh Adder: 64 ➔ 60
  - Blood Serpent: 62 ➔ 19
  - Ash Rattler: 54 ➔ 34
  - Bog Asp: 17 ➔ 7
* **Ladders (Bottom ➔ Top):**
  - Crypt Steps: 4 ➔ 14
  - Gallows Climb: 9 ➔ 31
  - Sanctuary: 20 ➔ 38
  - Watchtower: 28 ➔ 84
  - Ossuary: 40 ➔ 59
  - Belfry Bridge: 51 ➔ 67
  - Catacomb Rise: 63 ➔ 81
  - Altar Ladder: 71 ➔ 91

---

## 🛠️ Tech Stack

- **Three.js (r128)** — 3D rendering, scene management, lighting, and procedural geometries.
- **Web Audio API** — Real-time procedural audio synthesis.
- **Tailwind CSS** — Dark gothic HUD, glassmorphism modals, and responsive layout.
- **Pure JavaScript (ES6+)** — Zero build tools or Node.js dependencies required; runs directly in any modern browser.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/kishukrgupta/the-cursed-board.git
   ```
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Brave, Safari).
   - No `npm install`, server, or bundler needed!

---

## 📜 License

MIT License — Feel free to play, fork, and build upon it!
