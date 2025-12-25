# Tetris

Classic Tetris game implemented in vanilla JavaScript.

## Features

- Standard 7 tetromino pieces (I, O, T, S, Z, J, L)
- Score tracking with level progression
- Next piece preview
- Pause functionality
- Auto-save/load game state
- Responsive controls

## How to Play

Open `index.html` in browser.

### Controls

- `←` `→` - Move piece left/right
- `↑` - Rotate piece
- `↓` - Soft drop
- `Space` - Hard drop
- `P`/`Esc` - Pause
- `R` - Restart

## Gameplay

- Clear lines to score points
- Level increases every 10 lines cleared
- Game speeds up with each level
- Score multiplier increases with level

### Scoring

- 1 line: 100 × level
- 2 lines: 300 × level
- 3 lines: 500 × level
- 4 lines: 800 × level
- Hard drop: +2 per row

## Technical

- Pure JavaScript (no dependencies)
- LocalStorage for game persistence
- Modular architecture (Board, GameState, Renderer, InputHandler)
- 10×20 grid, 30px cells
