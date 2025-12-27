# Three-game

🎮 **Doom-Style First-Person Shooter Game** built with Three.js

![Game Screenshot](https://github.com/user-attachments/assets/e23ad9ee-345d-436c-a32e-a5f6232cf52a)

## 🕹️ Game Features

- **First-person shooter** gameplay inspired by classic Doom
- **3D environment** with maze-like walls and atmospheric lighting
- **Enemy AI** that tracks and attacks the player
- **Shooting mechanics** with hit detection
- **Health system** - avoid getting hit by enemies
- **Victory condition** - eliminate all enemies to win
- **Retro aesthetic** with red and dark themes

## 🎯 How to Play

### Controls
- **W, A, S, D** - Move forward, left, backward, right
- **Mouse** - Look around
- **Left Click** - Shoot
- **ESC** - Release mouse cursor

### Objective
Survive and eliminate all 5 enemies in the arena to win the game!

## 🚀 GitHub Pages Deployment

This game is ready to be deployed on GitHub Pages:

1. Go to your repository **Settings**
2. Navigate to **Pages** section (under "Code and automation")
3. Under "Source", select **Deploy from a branch**
4. Select branch: `copilot/create-doom-style-game`
5. Select folder: `/ (root)`
6. Click **Save**

Once deployed, your game will be available at:
```
https://skirep.github.io/Three-game/
```

## 🛠️ Technology Stack

- **Three.js** - 3D graphics library
- **PointerLockControls** - First-person camera controls
- Pure **HTML/CSS/JavaScript** - No build process required
- **ES6 Modules** - Modern JavaScript imports

## 📁 Project Structure

```
Three-game/
├── index.html        # Main game file (standalone, no dependencies)
├── .nojekyll        # Ensures GitHub Pages serves the site correctly
└── README.md        # This file
```

## 🎨 Game Elements

- **Dark maze environment** with multiple rooms
- **Dynamic lighting** with pulsing effects
- **Billboard sprite enemies** that always face the player
- **Fog effects** for atmosphere
- **UI overlay** showing health, ammo, and enemy count

## 💻 Local Development

To run the game locally:

```bash
# Start a simple HTTP server in the project directory
python3 -m http.server 8080

# Or use Node.js
npx http-server -p 8080

# Then open http://localhost:8080 in your browser
```

## 📝 Notes

- The game uses CDN-hosted Three.js library (no installation required)
- Works in all modern browsers that support ES6 modules
- Requires pointer lock API support (available in all modern browsers)

## 🎮 Gameplay Tips

- Keep moving to avoid enemy attacks
- Enemies deal 10 damage per hit
- You start with 100 health
- Stay aware of your surroundings - enemies can come from any direction
- Use walls for cover while engaging enemies

---

**Created with Three.js** - A WebGL-powered 3D graphics library