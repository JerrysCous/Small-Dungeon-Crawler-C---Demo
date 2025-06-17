# Text-Based Procedural Map Game

A simple C++ console game featuring a procedurally generated map, player and enemy characters, and basic movement controls.

---

## Features

- Procedurally generated 20x20 grid map with walls and random obstacles  
- Player (`P`) and enemy (`E`) spawn at opposite corners  
- Player movement using WASD keys (instant input, no Enter needed)  
- Collision detection preventing walking through walls  
- Randomized map layout on each run  

---

## How to Play

1. Clone or download this repository.  
2. Open the project in Visual Studio (tested with VS 2019/2022).  
3. Build and run the project (`Ctrl + F5`).  
4. Use the **W**, **A**, **S**, **D** keys to move the player around the map.  
5. Avoid walls (`#`), navigate open floor (`.`), and try to catch or avoid the enemy.

---

## Code Overview

- `Game.h` — Game class declaration, map size constants, and core members.  
- `Game.cpp` — Main game loop, procedural map generation, rendering, input handling, and updates.

---

## Future Improvements

- Add combat system with health and attacks  
- Implement smarter enemy AI with pathfinding  
- Add loot and inventory management  
- Expand map size dynamically or create multi-level maps

---

## Requirements

- Windows OS (uses `system("cls")` and `<conio.h>`)  
- Visual Studio or any C++ compiler that supports C++11 and above

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

Feel free to fork, improve, and share!

---

*Created by [Your Name or GitHub Handle]*
