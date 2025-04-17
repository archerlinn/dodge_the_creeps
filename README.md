# 🎮 Dodge the Creeps

Welcome to **Dodge the Creeps**, a fast-paced 2D survival game built using the [Godot Engine](https://godotengine.org/). This was my first project using Godot, created by closely following the official [First 2D Game tutorial](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html).

The goal? **Avoid the mobs** (a.k.a. creeps) for as long as you can, and see how high of a score you can rack up!

---

## 🚀 Gameplay

- Control your character with arrow keys (or WASD).
- Avoid randomly spawning enemies.
- Survive as long as possible — your score increases over time.
- Get hit once, and it’s game over.

---

## 🎓 What I Learned

This project helped me get hands-on experience with:

- ✅ Godot’s node system and scene instancing
- ✅ 2D player movement and collision handling
- ✅ Using timers and signals to control gameplay flow
- ✅ UI creation with `Label`, `Timer`, and `CanvasLayer`
- ✅ Scene transitions and game state management
- ✅ Exporting variables and organizing scripts

---

## 🛠️ Tech Stack

- **Engine**: Godot 4.x (or 3.x depending on your version)
- **Language**: GDScript
- **Assets**: Included with the Godot tutorial (player sprite, mobs, background)

---

## 🧠 How It Works

- Mobs are spawned at random locations along a path (`Path2D`) and move in randomized directions.
- The player is placed at a start position at the beginning of each game.
- A score timer tracks how long you've survived.
- The game ends when the player is hit, stopping all timers and playing a death sound.

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open it in the Godot Engine.
3. Press the **Play** button to run the game.
4. Use the Start button to begin dodging creeps!

---

## 📁 Project Structure Overview

```
DodgeTheCreeps/
├── Player.gd
├── Main.gd
├── HUD.tscn
├── Mob.tscn
├── Main.tscn
├── assets/
│   └── (sprites, sounds, background, etc.)
```

---

## 📷 Screenshots

<p align="center">
    <img src="screenshots/Screenshot%202025-04-17%20014655.png" alt="Gameplay Screenshot" width="25%"/>
    <img src="screenshots/Screenshot%202025-04-17%20014717.png" alt="Gameplay Screenshot" width="25%"/>
    <img src="screenshots/Screenshot%202025-04-17%20014750.png" alt="Gameplay Screenshot" width="25%"/>
</p>

---

## 💬 Acknowledgements

- Special thanks to the [Godot Documentation Team](https://docs.godotengine.org/) for the amazing step-by-step guide.
- Inspired by the official “Dodge the Creeps” tutorial project.

---

## 📌 Next Steps

Some features I'm considering for future versions:

- Power-ups or shields
- Leaderboard/high score tracker
- Gamepad or mobile support
- Increasing difficulty over time

---

## 📜 License

This project is for educational purposes and personal learning. Assets are sourced from the Godot tutorial and fall under their respective licenses.
