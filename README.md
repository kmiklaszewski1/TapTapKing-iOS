# Tap Tap King 🪐👑

Hyper-casual mobile game for iOS built in Unity. Cosmic tapping challenge: tap the planet button as fast as you can for 10 seconds to beat your personal records and climb the leaderboard!

## 🎮 Gameplay
- Tap the central planet-button as rapidly as possible.
- Timer: exactly 10 seconds per round.
- Score = number of taps; high score is tracked and saved locally.
- Instant restart and score comparison after each game.

## 🌌 Cosmic Theme
- Background: stars and cosmic gradient for immersive space atmosphere.
- Button: animated planet with tap counter in the center.
- Visual Effects: particle effects on every tap, neon-style UI elements.
- Smooth animations: responsive and fluid tap mechanics throughout gameplay.

## 🛠 Tech Stack
- **Engine**: Unity 6 with 2D URP (optimized for iOS mobile devices).
- **Language**: C# for all game scripts.
- **Core Scripts**: 
  - TapGameManager.cs - Handles game logic and tap counting.
  - UIManager.cs - Manages score display and UI updates.
  - PlayerPrefs integration - Persistent local score storage.
- **UI System**: Canvas Scaler for responsive design across all iPhone models.
- **Localization**: English.

## Build & Deployment
1. Open project in Unity Hub (Unity 6 or later recommended).
2. Go to Player Settings:
   - Platform: iOS
   - Orientation: Portrait
   - Bundle ID: com.yourname.taptapking
3. Build and run on Xcode → Archive → Upload to App Store Connect.
4. Test on physical iPhone devices for responsiveness and tap feedback.

## Project Structure
Assets/
├── Scenes/
│   └── MainGame.unity          # Main gameplay scene
├── Scripts/
│   ├── TapGameManager.cs       # Core game logic
│   └── UIManager.cs            # UI and score management
├── Sprites/
│   ├── planet.png              # Main tap button sprite
│   └── stars_bg.png            # Background texture
└── Prefabs/                    # Reusable UI elements

## Future Features
- Game Center Leaderboards integration for online high scores.
- Sound effects and haptic vibration feedback.
- Additional planet skins and cosmetic upgrades.
- Daily challenges and achievement system.
- Multiplayer competitive modes.

## Performance
- Optimized for iPhone 11 and newer models.
- Lightweight asset pipeline for quick app load times.
- Efficient tap detection with minimal CPU overhead.

## License
This project is part of my Game Development portfolio. Feel free to use as reference or inspiration for your own projects.

---

**Created by**: Kamil Miklaszewski
**Portfolio**: github.com/kmiklaszewski1
**Status**: Active Development
