
# Lottery Adventure Game

## Introduction
Lottery Adventure Game is an interactive text-based adventure game where players make choices to navigate through different paths and scenarios. The objective of the game is to find the hidden treasure while avoiding game-ending obstacles.

---

## Features
1. **Three Adventure Paths**:
   - **Forest**: Players can choose to explore the forest, deciding between climbing a tree or following a stream.
   - **Cave**: Players decide whether to light a torch or move in the dark, encountering shiny objects and traps.
   - **Mountain**: Players face choices like taking a narrow path or a steep climb, with opportunities to rest or continue.

2. **Replay Option**:
   - After a game ends, players can choose to replay and explore different paths.

3. **User-Friendly Input**:
   - Players are guided through each decision with clear instructions and feedback for invalid inputs.

---

## How to Play
1. Run the game script.
2. Start the game by choosing a path:
   - `A`: Enter the forest
   - `B`: Explore the cave
   - `C`: Climb the mountain
3. Follow the prompts and make decisions by typing the corresponding letters.
4. Reach the treasure to win or face obstacles that may end the game.
5. Replay the game to explore alternative paths and outcomes.

---

## Game Flow
### 1. **Start Game**
The game begins with a welcome message and three initial choices:
- Enter the forest (`A`)
- Explore the cave (`B`)
- Climb the mountain (`C`)

### 2. **Forest Path**
- Choose to go left (`L`) or right (`R`).
- Left Path:
  - Climb a tree (`T`): Lose the game.
  - Follow the stream (`S`): Find the treasure and win.
- Right Path:
  - Get lost and lose the game.

### 3. **Cave Path**
- Light a torch (`T`) or move in the dark (`D`).
  - Torch:
    - Inspect shiny object (`O`): Find treasure and win.
    - Avoid shiny object (`A`): Get trapped and lose.
  - Dark: Trip and lose the game.

### 4. **Mountain Path**
- Take a narrow path (`N`) or steep climb (`S`).
  - Narrow Path:
    - Rest (`B`): Find treasure and win.
    - Continue climbing (`C`): Fall and lose.
  - Steep Climb: Lose the game.

### 5. **Replay Game**
At the end of the game, players are prompted to replay (`Yes`) or exit (`No`).

---

## Code Highlights
- **Recursive Design**: Invalid inputs prompt the user to retry without exiting the game.
- **Case-Insensitive Input**: User inputs are converted to uppercase for consistency.
- **Modular Structure**: Functions for each path ensure code readability and ease of maintenance.

---

## Example Run
```
Welcome To Lottery Adventure Game
Start Your Adventure by choosing a path
A: Enter the forest
B: Explore the cave
C: Climb the mountain
Choose A, B, C: A

You are in the forest. Do you want to go left or right?
Enter L for left or R for right: L

You choose to go left. Do you want to climb a tree or follow the stream?
Enter T to climb a tree or S to follow the stream: S

You followed the stream and found the treasure, you win!

Do you want to play again (Yes or No): No
Thanks for playing! Goodbye!
```

---

## Requirements
- Python 3.x

---

## How to Run
1. Save the script to a file named `lottery_adventure_game.py`.
2. Open a terminal or command prompt.
3. Run the script using:
   ```
   python lottery_adventure_game.py
   ```
4. Follow the on-screen instructions.

---

## Future Improvements
- Add more adventure paths.
- Include a scoring system.
- Implement graphics or sound effects for enhanced user experience.

---

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

