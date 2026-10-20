  # 🐍 Retro Snake Game

A classic Snake game inspired by the old monochrome mobile phones of the early 2000s. Guide the snake around the box, eat the food, and grow longer — but don't hit the walls or yourself!

## 🎮 About the Game

- The game is played inside a box made of a grid of square cells.
- The snake moves one cell at a time and can only go in **4 directions**: up, down, left and right (no diagonal or curved movement).
- Food appears as a single dot on a random empty cell of the grid.
- Each time the snake eats the food, it grows by one block and your score goes up.
- The game gets a little faster every 5 food items eaten.

## 🕹️ Controls

| Action        | Keyboard               | Mobile                    |
|---------------|------------------------|---------------------------|
| Move Up       | ↑ Arrow / W            | Up button or swipe up     |
| Move Down     | ↓ Arrow / S            | Down button or swipe down |
| Move Left     | ← Arrow / A            | Left button or swipe left |
| Move Right    | → Arrow / D            | Right button or swipe right |
| Pause/Resume  | Space / P              | Pause button              |
| Restart       | Space (on Game Over)   | Tap the screen            |

## 📜 Rules

1. The snake starts with 3 blocks in the middle of the board, moving right.
2. Eat the food to grow longer and earn 1 point.
3. The snake cannot turn back directly into itself.
4. **Game Over** happens if the snake:
   - hits the border of the box, or
   - runs into its own body.

## ✨ Features

- Retro green LCD-style look with pixel graphics
- Grid-based, step-by-step movement just like the original
- Score and high score display (high score is saved in your browser)
- Speed increases as you progress
- Pause and resume
- Keyboard and touch/swipe controls
- Optional sound effects with a mute button

## 🚀 How to Run

No installation needed.

1. Download or clone this project.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Start playing!

```bash
git clone https://github.com/your-username/snake-game.git
cd snake-game
# then open index.html in your browser
```

## 📁 Project Structure

```
snake-game/
├── index.html   # The complete game (HTML, CSS and JavaScript)
└── README.md    # Project documentation
```

## 🛠️ Built With

- HTML5 Canvas
- CSS
- Vanilla JavaScript (no libraries or frameworks)

## 🔮 Future Ideas

- Difficulty levels (Easy / Medium / Hard)
- Maze levels with walls inside the box
- Bonus food that appears for a short time
- Wrap-around mode (pass through walls)

## 📄 License

This project is free to use and modify for learning and personal use.
