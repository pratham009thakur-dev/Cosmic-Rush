# Cosmic Rush 🚀🌌

Cosmic Rush is an arcade-style, space-themed browser obstacle runner built with vanilla JavaScript, modern CSS, and HTML5 Canvas. Navigate through asteroid belts, collect cosmic fuel, and dodge celestial hazards in a fast-paced survival challenge.

> **Current Architecture:** Frontend Browser Game Engine  
> **Backend Status:** Roadmap item for global high-score sync

---

## 🛠 Tech Stack
- **Frontend**: HTML5 Canvas, CSS3, JavaScript (ES6+)
- **Architecture**: Event-driven animation loop, coordinate-based hitboxes
- **Version Control & Hosting**: Git, GitHub, Netlify[cite: 1]

---

## ✨ Core Features
- **Fluid 60 FPS Canvas Engine**: Built using `requestAnimationFrame` for stutter-free gameplay and consistent frame-rate rendering across desktop browsers.
- **Dynamic Obstacle & Entity Generation**: Randomized asteroid clustering and celestial debris patterns that scale in frequency and velocity as survival time increases.
- **Precise Bounding-Box Collision Logic**: Pixel-calibrated hitboxes verifying spatial overlaps between the player spaceship, obstacles, and collectible energy cells.
- **Real-Time Heads-Up Display (HUD)**: On-screen telemetry providing live distance traveled, cosmic score counters, and shields/health remaining.
- **Audio & Visual Immersion**: CSS-driven neon UI effects coupled with event-triggered dynamic sound effects.

---

## 🗺️ Roadmap
- [ ] Centralized REST API server for persistent cross-platform leaderboards.
- [ ] Touch gestures and on-screen joystick overlays for mobile responsiveness.
- [ ] Power-up inventory system and unlockable ship skins.

---

## 🚀 Running Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/pratham009thakur-dev/cosmic-rush.git](https://github.com/pratham009thakur-dev/cosmic-rush.git)
   ```
2. Navigate into the directory:
   ```bash
   cd cosmic-rush
   ```
3. Open `index.html` directly in any modern web browser.