
# 🎮JavaScript Car Racing Game

Is a retro-style 2D car racing game built entirely with HTML, CSS, and vanilla JavaScript. Inspired by classic arcade racing games, Dash lets players race against time, dodge traffic, and aim for high scores in a fast-paced, colorful environment.

---
## 🚗 Gameplay Features

- 🏁 **Arcade racing** mechanics with pixel art visuals
- 🚗 **Smooth car controls** using keyboard arrows
- 🧠 **AI-controlled cars** (obstacles) to avoid
- ⏱️ **Score, time, lap timer, and speedometer**
- 💽 **Retro-styled audio effects** (engine, honk, theme)
- 🌥️ Animated clouds, moving road, and roadside trees
- 💾 High score tracking in-session
- 📱 Fully browser-based – no installation needed

---

## 🎮 Controls

| Key         | Action              |
|-------------|---------------------|
| `C`         | Insert Coin / Start |
| `M`         | Mute Sound          |
| `←` or `→`  | Move Left / Right   |
| `↑` or `↓`  | Accelerate / Brake  |
| `ESC`       | Reset Game          |

---

## 📂 Project Structure

```
dash-racing-game/
├── index.html
├── icon.png
├── javascript/
│   ├── 1.js
│   └── null.js
├── images/
│   ├── car04.png
│   ├── tree.png
│   ├── cloud.jpg
│   ├── finish.png
│   └── hero.png
└── README.md
```

---

## 🛠️ Technologies Used

- **HTML5** for game canvas structure
- **CSS3** for retro-style UI and animations
- **JavaScript (Vanilla)** for game logic, rendering, and controls
- **Web Audio API** for immersive background and event sounds

---

## 🚀 Getting Started

### 🧪 Play Locally

1. **Clone or download** the repository:
   ```bash
   git clone https://github.com/Creativedelight/Car_Race_Game.git
   cd dash-racing-game
   ```

2. **Open** `index.html` in your browser:
   ```bash
   open index.html
   # or double-click the file
   ```

---

## 🧠 How It Works

- The game renders a continuous road using perspective projection.
- `Lines` define road segments with curvature and elevation.
- AI cars are positioned and moved using modular lanes and randomized logic.
- Player speed, position, and score are updated in the game loop.
- Collisions are detected and impact the speed and sound effects.
- Audio assets are streamed via Web Audio API.

---

## 📌 To-Do (Improvements & Ideas)

- 🏎️ Add car selection or upgrades
- 🏆 Store highscores using browser localStorage
- 📱 Make UI touch-friendly for mobile
- 🌍 Add multiplayer or ghost replays
- 🛣️ Add additional track layouts or obstacles

---

## 👩‍💻 Author

**Faith M.** — [GitHub](https://github.com/Creativedelight)
Passionate about building interactive web apps and arcade-inspired games.

---


