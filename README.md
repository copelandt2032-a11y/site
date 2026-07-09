# 🎮 Unblocked Games Hub

A collection of classic browser-based games that can be played anytime, anywhere. All games run entirely in your browser with no external dependencies.

## Games Included

### ⭕ Tic Tac Toe
The classic strategy game for two players. X and O take turns marking spaces on a 3×3 grid. First to get three in a row wins!

**How to Play:**
- Click on an empty square to place your mark
- Get 3 in a row (horizontal, vertical, or diagonal) to win
- Click "New Game" to reset

### 🐍 Snake
Navigate your snake to eat food and grow longer. Avoid hitting the walls or yourself!

**How to Play:**
- Use Arrow Keys or WASD to control the snake
- Eat red food to grow and earn points
- Don't hit the walls or your own tail
- Each food eaten adds 10 points

### 🔢 2048
Combine tiles with the same number to reach 2048. A puzzle game of strategy and math.

**How to Play:**
- Use Arrow Keys to slide tiles
- When two tiles with the same number collide, they merge into one
- The goal is to create a tile with the value 2048
- Your best score is saved automatically

### 🐦 Flappy Bird
A fast-paced game where you guide a bird through obstacles. How many pipes can you pass?

**How to Play:**
- Click or press SPACE to make the bird fly upward
- Avoid hitting the pipes (obstacles)
- You score 1 point for each pipe pair you successfully pass
- Keep your reflexes sharp!

## Getting Started

### Play Online
Simply open `index.html` in your web browser to start playing!

### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/copelandt2032-a11y/site.git
   cd site
   ```

2. Open `index.html` in your favorite browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000` in your browser

## Features

✅ **No Installation Required** - Just open and play  
✅ **No External Dependencies** - Pure HTML, CSS, and JavaScript  
✅ **Responsive Design** - Works on desktop, tablet, and mobile  
✅ **Data Persistence** - Best scores saved in browser storage  
✅ **Accessibility** - Keyboard controls for all games  

## File Structure

```
site/
├── index.html              # Landing page with game menu
├── styles.css              # Main styles
└── games/
    ├── tictactoe.html     # Tic Tac Toe game
    ├── snake.html         # Snake game
    ├── 2048.html          # 2048 game
    └── flappybird.html    # Flappy Bird game
```

## Browser Compatibility

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Any modern browser supporting HTML5, CSS3, and ES6 JavaScript

## Technologies Used

- **HTML5** - Canvas for 2D graphics
- **CSS3** - Responsive design with gradients and flexbox
- **JavaScript (ES6+)** - Game logic and interactivity
- **LocalStorage** - Persistent score tracking

## Tips & Tricks

### Tic Tac Toe
- The center square is the most valuable position
- Try to create two threats at once to win

### Snake
- Plan your path ahead to avoid getting trapped
- The more you eat, the harder it gets!

### 2048
- Try to keep the highest value in one corner
- Build up smaller tiles before attempting big merges

### Flappy Bird
- Timing is everything - tap at the right moment
- The gap between pipes is your target zone

## Contributing

Want to add more games? Feel free to submit pull requests! Game suggestions:
- Pong
- Breakout
- Pac-Man
- Tetris

## License

This project is open source and available under the MIT License.

## Credits

Created as a fun collection of classic games for entertainment. Enjoy!

---

**Have Fun! 🎮**

