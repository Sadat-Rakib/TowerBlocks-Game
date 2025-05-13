# Tower Blocks Game

A challenging and addictive 3D stacking game where players must carefully place blocks on top of each other to build the tallest tower possible.

## ✨ Features

- Smooth 3D graphics powered by Three.js
- Responsive design that works on desktop and mobile devices
- Simple one-click/tap or spacebar controls
- Progressive difficulty as your tower grows taller
- Animated game effects using GSAP animations
- Minimalist design with focus on gameplay

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript (for development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sadat-Rakib/TowerBlocks-Game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd TowerBlocks-Game
   ```

3. Open `index.html` in your web browser to play the game locally.

### Development Setup

For development, you can use a local server to avoid CORS issues when loading assets:

```bash
# Using Python 3
python -m http.server

# Using Node.js with http-server
npm install -g http-server
http-server
```

## 🎯 How to Play

1. Click the "Start" button to begin the game
2. As blocks move across the screen, click, tap, or press the spacebar to place them
3. Try to align each new block with the one below it
4. The game ends when a block misses the tower completely
5. Aim to build the tallest tower possible and achieve the highest score!

## 🛠️ Technology Stack

- HTML5
- CSS3
- JavaScript
- [Three.js](https://threejs.org/) - 3D graphics library
- [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/) - Animation library

## 📁 Project Structure

```
TowerBlocks-Game/
├── index.html          # Main HTML file
├── style.css           # Main CSS styles
├── style.scss          # SCSS source (if using Sass)
├── main.js             # Main JavaScript game logic
├── main.ts             # TypeScript source (if using TypeScript)
├── .godo/              # Project configuration folder
└── README.md           # This file
```

## 🧩 Game Mechanics

The game follows these core mechanics:

1. Blocks move horizontally across the screen
2. Player timing determines block placement
3. Perfect alignment adds to score
4. Partial alignment causes the block to split
5. Block speed increases as the tower grows taller
6. Game ends when a block completely misses the tower

## 🔮 Future Enhancements

- Add sound effects and background music
- Implement different themes/color schemes
- Add power-ups and special blocks
- Create a global leaderboard
- Add difficulty levels

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic stacking games
- Three.js community for the excellent 3D library
- Original concept based on similar arcade games

---

Made with ❤️ by Sadat-Rakib
