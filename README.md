# web-game — Arcade Hub

A small collection of browser games, playable with mouse/keyboard on PC or touch on mobile. No build step, no dependencies — plain HTML/CSS/JS.

## Games

- Snake
- 2048
- Tic-Tac-Toe (vs unbeatable AI or 2-player)
- Memory Match
- Breakout
- Whack-a-Mole
- Flappy Bird
- Simon Says
- Minesweeper
- Pong (vs CPU)
- Connect Four (vs unbeatable-ish AI or 2-player)
- Rock Paper Scissors
- Hangman
- Slide Puzzle (8/15-puzzle)
- Blackjack
- Reaction Test
- Word Guess (Wordle-style)
- Space Invaders
- Dino Runner
- Tetris

## Running it

Any static file server works, e.g.:

```bash
npx serve .
# or
python -m http.server 8000
```

Then open `index.html` (or `http://localhost:PORT`) in a browser. Opening `index.html` directly via `file://` also works.

High scores are saved per-device in the browser's `localStorage`.
