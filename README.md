# 🏎️ NEON STREET RACER

**A neon-powered arcade racing game built with HTML5 Canvas, CSS, and vanilla JavaScript — all in one HTML file!**

Race through a glowing futuristic city, dodge traffic, collect coins, activate nitro, and beat your high scores in this fast-paced arcade racing experience.

## 🌃 Overview

NEON STREET RACER is a browser-based 2D racing game designed to deliver an exciting arcade experience without complicated setup, external assets, or additional dependencies.

The project is designed around a **single standalone `index.html` file**, containing the game's HTML, CSS, and JavaScript.

## ✨ Features

- 🏁 **Arcade Racing:** Three-lane highway racing with smooth steering and responsive movement.
- 🌆 **Neon City:** Futuristic nighttime scenery, glowing road markings, and colorful visual effects.
- 🚗 **Traffic System:** Avoid enemy vehicles and survive increasingly challenging traffic.
- ⚡ **Nitro Boost:** Activate extra acceleration for high-speed racing.
- 🪙 **Collectibles:** Gather coins and power-ups during your runs.
- 💥 **Crash Effects:** Collisions, sparks, smoke, and screen-shake effects.
- 🎮 **Multiple Game Modes:** Endless Racing, Time Challenge, Coin Collector, and Traffic Survival.
- 🛠️ **Garage:** Choose vehicles, customize designs, and unlock cars with collected coins.
- 📊 **Progress Tracking:** Scores, distance, coins, high scores, and gameplay statistics.
- 🔊 **Procedural Audio:** Optional synthesized sound effects using the Web Audio API.
- 📱 **Responsive Controls:** Keyboard controls for desktop and touch controls for mobile.
- 💾 **Local Saving:** Save supported game progress and settings using browser local storage.
- ⏸️ **Game States:** Main menu, pause screen, game-over screen, and restart functionality.

> **Note:** Features listed above describe the intended project scope. Verify each feature against the current source code before treating it as implemented.

## 🕹️ Controls

| Action | Keyboard |
|---|---|
| Steer left | `←` or `A` |
| Steer right | `→` or `D` |
| Accelerate | `↑` or `W` |
| Brake | `↓` or `S` |
| Activate nitro | `Space` |
| Pause / Resume | `P` or `Esc` |
| Start / Restart | `Enter` |

On mobile devices, use the on-screen touch controls when available.

## 🚀 Getting Started

No installation, build tools, or server are required for the standalone game.

1. Clone or download this repository.
2. Locate `index.html`.
3. Open `index.html` in a modern web browser.
4. Start racing!

### Run locally

```bash
git clone https://github.com/bytevorax-debug/NEON-RACING-GAME---HTML-FILE-.git
cd NEON-RACING-GAME---HTML-FILE-
```

Then open `index.html` in your browser.

Alternatively, download the repository as a ZIP file and open the HTML file directly.

## 🧰 Technologies

- **HTML5** — Page structure and game interface.
- **CSS3** — Neon styling, layouts, gradients, and animations.
- **JavaScript (Vanilla)** — Game mechanics, input handling, progression, and AI.
- **HTML5 Canvas API** — Real-time rendering of the road, vehicles, scenery, and effects.
- **Web Audio API** — Optional synthesized audio.
- **localStorage** — Persistent local progress and settings.

No third-party JavaScript libraries are required by the intended standalone design.

## 🏆 Game Modes

| Mode | Objective |
|---|---|
| Endless Racing | Survive as long as possible while difficulty increases. |
| Time Challenge | Earn the highest score before time runs out. |
| Coin Collector | Collect coins while avoiding traffic. |
| Traffic Survival | Survive progressively harder traffic waves. |

Availability and behavior depend on the features implemented in the current version.

## 💾 Save Data

Where implemented, the game uses browser `localStorage` to preserve progress, including:

- High scores and best distance.
- Collected coins and unlocked vehicles.
- Selected vehicle.
- Audio and gameplay settings.
- Gameplay statistics.

Save data is stored locally in the browser and is not automatically shared between devices or browsers. Clearing browser storage may erase saved progress.

## 📱 Compatibility

The game is intended for modern browsers that support HTML5 Canvas and JavaScript, including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Opera
- Safari

Performance may vary depending on the device and browser.

## 🧪 Development and Testing

When developing or updating the game, verify the following:

- All menu buttons and game modes work correctly.
- Steering, acceleration, braking, and nitro respond properly.
- Collisions and power-ups behave as expected.
- Pause, resume, restart, and game-over transitions work.
- Save data remains valid across reloads.
- The canvas resizes correctly on desktop and mobile.
- The game remains playable when audio is unavailable.
- The game works offline after the HTML file has been saved locally.

## 📂 Project Structure

```text
NEON-RACING-GAME---HTML-FILE-/
└── index.html    # Game markup, styles, and JavaScript
```

The intended architecture keeps all game code in a single file for easy sharing, portability, and offline use.

## 🎯 Project Goals

- Build an engaging arcade racing experience using browser-native technologies.
- Demonstrate Canvas rendering and real-time game-loop techniques.
- Explore collision detection, AI traffic, particle effects, and game progression.
- Keep the project accessible without a complex development environment.
- Provide a foundation for future improvements and new game modes.

## 🔮 Future Improvements

Potential additions include:

- More vehicles and unlockable designs.
- Additional city environments and road themes.
- Improved opponent AI and traffic behavior.
- More achievements and progression rewards.
- Additional accessibility and mobile-control options.
- Performance optimizations and expanded gameplay statistics.

## 👨‍💻 Author

Created by **[BytevoraX](https://github.com/bytevorax-debug)**.

GitHub Repository: [NEON-RACING-GAME---HTML-FILE-](https://github.com/bytevorax-debug/NEON-RACING-GAME---HTML-FILE-)

## 📜 License

No license is specified in this README. Add a `LICENSE` file if you want to establish explicit terms for copying, modifying, and distributing the project.

---

**Start your engine. Hit the nitro. Own the neon streets!** 🏁⚡
