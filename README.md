# 🐍 Snake Game in C++ (Windows Console)

A classic **Snake Game** implemented in C++ using Windows-specific libraries like `windows.h` and `conio.h`. The game runs in the terminal and uses real-time keyboard input (`W`, `A`, `S`, `D`) for controlling the snake.

---

## 🚀 Features

- Console-based snake movement
- Real-time keyboard input (no Enter key required)
- Food spawning with scoring system
- Game-over on self or wall collision
- Lightweight and fast

---

## 🎮 Controls

| Key | Action     |
|-----|------------|
| W   | Move Up    |
| A   | Move Left  |
| S   | Move Down  |
| D   | Move Right |

---

## 🧱 Requirements

- Windows OS
- C++ compiler (e.g., `g++` from MinGW)
- Console window (CMD or PowerShell)

> ⚠️ This game uses `windows.h`, so it won't compile or run on Linux or macOS without significant modification.

---

## 🔧 Compilation

Use a terminal with `g++`:

```bash
g++ snake_game.cpp -o snake_game




Run it with:


./snake_game
You may need to use g++ -std=c++11 snake_game.cpp -o snake_game if C++11 features are used.



The snake is represented as an array of Point structs.

Movement is done by updating the head and shifting body parts.

conio.h functions like kbhit() and getch() enable real-time input.

windows.h handles cursor control and screen dimensions.

File Structure

snake_game.cpp      # Main game file
README.md           # This file
#   S n a k e G a m e - i n - C P P  
 