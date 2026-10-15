# Pong (Web Edition)

A classic Pong arcade game built with Python and Pygame-CE. Defend your paddle and hit the ball past your opponent.

Playable locally and in modern web browsers via WebAssembly ([Pygbag](https://pygame-web.github.io/)).

## How to Run Locally

### Prerequisites
- Python 3.10+
- `pip install pygame-ce pygbag`

### Play Locally
```bash
python main.py
```

### Run in Browser Locally
```bash
python -m pygbag main.py
```
Open `http://localhost:8000` in your web browser.

## Controls
- **W / S** or **Up / Down Arrow Keys**: Move paddle
- **Space**: Serve ball / restart
- **Escape**: Quit game
