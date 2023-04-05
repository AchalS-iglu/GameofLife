# GameofLife

A Python implementation of Conway's Game of Life.

## Description

This program simulates a two-dimensional grid of cells, where each cell can either be alive or dead. The grid evolves over time according to certain rules:

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

By applying these rules repeatedly, the program generates interesting patterns and shapes that evolve over time.

## Technologies Used

- Python

## Credits

This program was inspired by [this article](https://betterprogramming.pub/how-to-write-conwells-game-of-life-in-python-c6eca19c4676).
