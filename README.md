# Pong

[![Python](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Pygame-ce](https://img.shields.io/badge/pygame--ce-latest-green.svg)](https://github.com/pygame-community/pygame-ce)
[![Pygbag](https://img.shields.io/badge/pygbag-latest-pink.svg)](https://github.com/pygame-web/pygbag)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/ShivamKR12/Pong?include_prereleases&style=flat-square)](https://github.com/ShivamKR12/Pong/releases)
[![pygbag build](https://img.shields.io/github/actions/workflow/status/ShivamKR12/Pong/pygbag.yml?branch=web)](https://github.com/ShivamKR12/Pong/actions)

A modern implementation of the classic **Pong** arcade game built with **Python** and **Pygame-CE**. This project features an object-oriented architecture, sprite-based collision detection, AI opponent, sound effects, score tracking, and a clean, maintainable codebase.

> **Repository Structure**
>
> This repository contains three independent branches:
>
> * **desktop** *(default)* — Native Windows/Desktop version
> * **web** — Browser version built with `pygbag` (this branch)
> * **android** — Android version *(currently in development)*

---

## Table of Contents
- Features
- Requirements
- Running the Game
- Controls
- Building for Web
- Project Structure
- Screenshots
- Branches
- Technologies Used
- License
- Author

---

## Features

* 🏓 Classic Pong gameplay
* 🤖 AI-controlled opponent
* 🎮 Smooth paddle controls
* 💥 Sprite-based collision detection
* 🔊 Sound effects
* ⏱️ Countdown before each serve
* 📊 Live score tracking
* 🧱 Object-oriented architecture
* ⚡ 120 FPS gameplay

---

## Requirements

* Python 3.10+
* Pygame-ce
* Pygbag

Install the required dependency:

```bash
pip install pygame-ce pygbag
```

---

## Running the Game

From the project directory:

```bash
pygbag main.py
```

---

## Controls

| Key | Action           |
| --- | ---------------- |
| ↑   | Move paddle up   |
| ↓   | Move paddle down |

---

## Building for Web

This project uses **pygbag** to package the Python application for the web, allowing it to run in a browser.

To build the project, run the following command from the project's root directory:

```bash
pygbag --build main.py
```

---

## Project Structure

```text
Pong
│
├── .github
│   └── actions
│       └── build.yml
│
├── assets/
│   ├── Ball.png
│   ├── Paddle.png
│   ├── pong.ogg
│   └── score.ogg
│
├── favicons/
│
├── main.py
├── pygbag.ini
├── LICENSE
├── README.md
└── .gitignore
```

---

## Branches

This repository hosts multiple platform-specific versions of the game.

| Branch      | Description                             |
| ----------- | --------------------------------------- |
| **desktop** | Native desktop version for Windows, macOS, and Linux (default branch) |
| **web**     | Browser version built using `pygbag` (this branch) |
| **android** | Android version *(work in progress)*    |

Each branch evolves independently and has its own:

* README
* Assets
* Features
* GitHub Actions
* Release builds
* Commit history

---

## Technologies Used

* Python
* Pygame
* pygbag
* Git
* GitHub Actions

---

## License

This project is released under the [MIT License](LICENSE).

---

## Author

**Shivam Kumar**
