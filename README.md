# Tic-Tac-Toe Circuit

This project implements a **Tic-Tac-Toe** game using digital logic circuit design. The design is created in **Logisim** and simulates the functioning of a two-player Tic-Tac-Toe game.

## Features

- Two-player Tic-Tac-Toe game.
- Designed using basic logic gates and flip-flops.
- Simple and intuitive layout in **Logisim**.
- Allows players to take turns marking cells on a 3x3 grid.
- Detects the winner (or a draw) and highlights the result.

## Requirements

- [Logisim](http://www.cburch.com/logisim/) or any other software capable of opening `.circ` files.
  
## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-circuit.git
   ```
2. Open **Logisim** on your computer.
3. In **Logisim**, open the `TIC_TAC_TOE.circ` file.
   - Go to **File** > **Open** and select the `.circ` file.
4. Simulate the circuit and play the Tic-Tac-Toe game by interacting with the grid and selecting player turns.

## Circuit Design Overview

- **Grid**: The 3x3 grid is implemented using logic gates to simulate the cells.
- **Player Input**: Each player inputs their move, which is registered on the grid.
- **Win Detection**: Logic is implemented to check for winning combinations (horizontal, vertical, or diagonal).
- **Reset**: A reset mechanism is available to start a new game.

## Future Enhancements

- Add a graphical interface over the circuit for a more user-friendly experience.
- Extend the game to support AI for single-player mode.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and create a pull request.

---
