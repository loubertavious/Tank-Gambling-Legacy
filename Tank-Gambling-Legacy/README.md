# Tank Gambling - Retro CRT Tank Battle Game

A retro-styled tank battle game with CRT effects, upgrade system, and multiple game modes. Built with vanilla HTML5, CSS3, and JavaScript.

![Tank Gambling Game](https://img.shields.io/badge/Game-Tank%20Gambling-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Game Features

### Game Modes
- **Versus Mode**: 1v1 tank battles with upgrade system
- **Zombies Co-op**: Team up to survive waves of AI enemies
- **Boss Battles**: Epic boss fights every 5th wave in zombies mode

### Core Gameplay
- **Tank Combat**: WASD/Arrow controls with shooting mechanics
- **Maze Navigation**: Procedurally generated mazes with wall collisions
- **Upgrade System**: 20+ unique perks with pros and cons
- **Ricochet Physics**: Bullets bounce off walls and enemies
- **Landmines**: Strategic mine placement system

### Visual Effects
- **CRT Monitor Effects**: Scanlines, glow, and curvature
- **Motion Trails**: Retro phosphor persistence
- **Particle Systems**: Explosions and death animations
- **Screen Shake**: Impact feedback
- **Health Bars**: Visual damage indicators

### Audio System
- **Retro SFX**: Procedurally generated sound effects
- **Background Music**: Looping atmospheric tracks
- **Volume Controls**: Separate music and SFX controls
- **Mute Options**: Global and music-only mute

## 🎯 Controls

### Player 1 (Pink Tank)
- **Movement**: WASD
- **Shoot**: F
- **Menu Navigation**: WASD + E

### Player 2 (Blue Tank)
- **Movement**: Arrow Keys
- **Shoot**: /
- **Menu Navigation**: Arrow Keys + .

### Game Controls
- **Restart**: R
- **Mute All**: M
- **Mute Music**: N
- **Dev Menu**: DEV MENU button

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tank-gambling.git
   cd tank-gambling
   ```

2. **Add background music** (optional)
   - Create a `music/` folder
   - Add `background.mp3` file
   - Music will start on first user interaction

3. **Open the game**
   - Open `tank_gambling_prototype_CRT_V_09_05.html` in your browser
   - Click anywhere to start music
   - Select game mode and start playing!

## 🎵 Audio Setup

### Background Music
1. Create a `music/` folder in the project directory
2. Add your `background.mp3` file
3. Music will automatically loop throughout the game

### Recommended Music
- **Style**: Upbeat, energetic track
- **Duration**: 2-4 minutes (will loop)
- **Volume**: Balanced to not overpower game sounds

## 🎲 Upgrade System

### Perk Rarities
- **Common** (White): Basic effects with small trade-offs
- **Rare** (Blue): Enhanced effects with moderate costs
- **Legendary** (Gold): Powerful effects with significant drawbacks
- **Mythical** (Rainbow): Game-breaking effects with extreme costs

### Example Perks
- **Rapid Fire**: +25% fire rate, -15% bullet speed
- **Heavy Rounds**: +2 damage, -20% fire rate
- **Ricochet**: +2 bounces, -25% bullet speed
- **Multishot**: +2 bullets per shot, -15% bullet speed
- **Piss Missile**: +1000% fire rate, -90% movement speed

## 🛠️ Development

### Dev Menu Features
- **Perk Testing**: Give any perk to any player
- **Match Controls**: Start different game modes
- **Player Tweaks**: Heal, modify stats
- **Music Controls**: Volume slider and toggle

### File Structure
```
tank-gambling/
├── tank_gambling_prototype_CRT_V_09_05.html  # Main game file
├── music/                                    # Background music folder
│   └── background.mp3                        # Background music track
├── README.md                                 # This file
└── music_setup_instructions.md              # Audio setup guide
```

## 🎨 Technical Details

### Technologies Used
- **HTML5 Canvas**: Game rendering
- **Web Audio API**: Sound generation and music playback
- **CSS3**: CRT effects and animations
- **Vanilla JavaScript**: Game logic and controls

### Browser Compatibility
- **Chrome**: Full support
- **Firefox**: Full support
- **Safari**: Full support
- **Edge**: Full support

### Performance
- **60 FPS**: Smooth gameplay
- **Responsive**: Adapts to different screen sizes
- **Lightweight**: Single HTML file with embedded assets

## 🎮 Game Modes Explained

### Versus Mode
- **Objective**: First to 5 round wins
- **Upgrades**: Loser gets to choose an upgrade after each round
- **Strategy**: Balance risk vs reward with perk choices

### Zombies Co-op
- **Objective**: Survive as many waves as possible
- **Progression**: Zombies get faster and stronger each wave
- **Boss Waves**: Every 5th wave features a powerful boss
- **Upgrades**: Earn perks by getting kills

## 🐛 Known Issues

- Music requires user interaction to start (browser security)
- Some older browsers may not support Web Audio API
- Gamepad support is experimental

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Press Start 2P Font**: Google Fonts
- **CRT Effects**: Custom CSS animations
- **Sound Design**: Procedurally generated with Web Audio API

## 🎯 Future Features

- [ ] Online multiplayer
- [ ] More game modes
- [ ] Custom maps
- [ ] Achievement system
- [ ] Leaderboards
- [ ] Mobile controls

---

**Enjoy the retro tank battle experience!** 🎮💥
