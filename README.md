# Conway's Game of Life

Welcome to the Conway's Game of Life repository! This project implements the cellular automaton devised by mathematician John Horton Conway in 1970. The Game of Life simulates the evolution of cells on a grid based on a set of simple rules.

![Conway's Game of Life Demo](game_of_life(7).gif)

## Description

Conway's Game of Life is a zero-player game that demonstrates how complexity can emerge from simple rules. The game is played on an infinite grid of square cells, each of which can be in one of two states: alive or dead. The state of each cell evolves based on its neighbors.

## How It Works

- **Rules**:
  1. Any live cell with fewer than 2 live neighbors dies (underpopulation).
  2. Any live cell with 2 or 3 live neighbors lives on to the next generation (survival).
  3. Any live cell with more than 3 live neighbors dies (overpopulation).
  4. Any dead cell with exactly 3 live neighbors becomes a live cell (reproduction).

## Features

- **Customizable Grid**: Adjust the size of the grid.
- **Initial Configurations**: Choose from predefined patterns or create your own.
- **Generation Control**: Step through generations manually or run the simulation continuously.
- **Visualization**: Clear and dynamic visualization of cell states.

## Getting Started

### Prerequisites

To run the Game of Life, you will need:

- Python 3.x
- Libraries: `numpy`, `matplotlib` (if visualization is implemented with these libraries)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/nabayansaha/Conway-s-Game-of-Life.git
    cd Conway-s-Game-of-Life
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Set the initial configuration of cells.
2. Run the simulation:
    ```sh
    python game_of_life.py
    ```
3. Observe the evolution of the grid.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the existing style and includes relevant tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- John Horton Conway for creating the Game of Life.
- Wikipedia for detailed information on Conway's Game of Life.
