# RPS 9000

Welcome to **RPS 9000**, a Rock-Paper-Scissors game implemented in Python! Test your skills against the AI and see if you can come out on top.

---

## Features

- Choose between **rock**, **paper**, or **scissors**.
- Play against a simple AI opponent.
- Visual feedback with emojis for moves:
  - Rock: 💎
  - Paper: 📜
  - Scissors: ✂️
- Handles invalid inputs gracefully.
- Option to exit the game at any time.

---

## How to Play

1. Run the program using Python.

   ```bash
   python rps_9000.py
   ```

2. The program will prompt you to choose your move:

    ```bash
    rock, paper, or scissors? >>
    ```

3. Enter one of the following:

    ```bash
    - rock
    - paper
    - scissors
    - Or type exit to quit the game.
    ```

4. After entering a move:

    ```bash
    - Your move and the AI's move will be displayed.
    - The program will announce the result (win, lose, or tie).
    ```

5. Repeat as many times as you'd like!

## Code Overview

### Classes and Methods

-**RPS Class**

-Handles the logic of the Rock-Paper-Scissors game.

**play_game()**

- Prompts the user for input.

- Validates the user's move and randomly selects an AI move.

- Calls methods to display moves and determine the result.

 **display_moves(user_move, ai_move)**

- Displays the player's and AI's moves with emojis.

**check_move(user_move, ai_move)**

- Determines and announces the result of the round.

## Requirements

```bash
Python 3.6 or higher.
No external dependencies are required; the game uses Python's standard library.
```

## Example Gameplay

```markdown

Welcome to RPS 9000!

rock, paper, or scissors? >> rock

----

You: 💎

AI: ✂️

----

You win

rock, paper, or scissors? >> paper

----

You: 📜

AI: 💎

----

You win
rock, paper, or scissors? >> exit
Thanks for playing
```

## Future Improvements

- Add more moves like lizard and spock to spice things up!
- Implement a scoring system to track wins, losses, and ties.
- Add a GUI for a more interactive experience.

## License

This project is licensed under the MIT License. Feel free to modify and share!