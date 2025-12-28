# Three-game

🎮 **Doom-Style First-Person Shooter Game** built with Pure JavaScript Raycasting

![Game Screenshot](https://github.com/user-attachments/assets/ecfc60fd-15d8-4f2f-a257-203731d1f4cc)

## 🕹️ Game Features

- **First-person shooter** gameplay inspired by classic Doom/Wolfenstein 3D
- **Raycasting 3D engine** - authentic retro rendering technique
- **Doom-style sprite enemies** - billboard sprites that always face the player
- **Enemy AI** that tracks and attacks the player
- **Shooting mechanics** with hit detection
- **Health system** - avoid getting hit by enemies
- **Victory condition** - eliminate all enemies to win
- **Retro aesthetic** with red and dark themes
- **No external dependencies** - runs entirely in the browser

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

- **Custom Raycasting Engine** - Built from scratch in pure JavaScript
- **Canvas 2D API** - Efficient rendering without WebGL
- **Pointer Lock API** - First-person camera controls
- Pure **HTML/CSS/JavaScript** - No build process or external dependencies
- **No CDN dependencies** - Everything runs locally for maximum reliability

## 📁 Project Structure

```
Three-game/
├── index.html        # Main game file (standalone, no dependencies)
├── .nojekyll        # Ensures GitHub Pages serves the site correctly
└── README.md        # This file
```

## 🎨 Game Elements

- **Raycasted 3D maze** with walls rendered using classic Doom technique
- **Depth-based shading** - walls get darker with distance
- **Billboard sprite enemies** with Doom-style rendering (red demons with yellow eyes)
- **Collision detection** for realistic movement
- **UI overlay** showing health, ammo, and enemy count
- **Crosshair** for aiming

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

- The game runs entirely in pure JavaScript with no external dependencies
- Works in all modern browsers that support Canvas 2D and Pointer Lock API
- No installation or build process required - just open index.html
- Uses authentic raycasting technique like the original Wolfenstein 3D and Doom

## 🎮 Gameplay Tips

- Keep moving to avoid enemy attacks
- Enemies deal 10 damage per hit
- You start with 100 health
- Stay aware of your surroundings - enemies can come from any direction
- Use walls for cover while engaging enemies

---

**Created with Pure JavaScript Raycasting** - A classic 3D rendering technique used in Wolfenstein 3D and early Doom engines