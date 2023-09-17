# Sudoku_Solver
The Sudoku Solver Using Backtracking is a JavaScript-based web application that allows users to solve Sudoku puzzles effortlessly.

## Table of Contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithm](#algorithm)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sudoku is a popular number puzzle game that requires filling a 9x9 grid with digits from 1 to 9. The challenge lies in ensuring that each column, each row, and each of the nine 3x3 subgrids, known as "boxes," contains all the digits from 1 to 9 without repetition.
This project provides a user-friendly interface where player can input Sudoku puzzles and instantly find solutions using the efficient backtracking algorithm. The application also includes a "Clear Board" button to reset the puzzle and start a new.

## Demo

[CLICK HERE!](https://drive.google.com/file/d/1bEvFnP2WsMsNjUBGArBa4MsJHROomswZ/view?usp=sharing)

## Features

- Solves Sudoku puzzles of varying difficulty levels.
- Easy-to-use JavaScript code for solving Sudoku.
- Backtracking algorithm guarantees a correct solution if one exists.
- Customizable to different grid sizes and puzzle configurations.

## Installation

Clone this repository or download the source code to your local machine.

```bash
git clone https://github.com/NITHES2003/Sudoku_Solver.git
```
## Usage

Run the HTML file in a web browser, and user can now fill in the Sudoku table, click "Solve" to find the solution, and click "Clear Board" to clear the table and start again.

## Algorithm

This Sudoku solver employs the backtracking algorithm, a recursive approach that systematically fills in cells while ensuring the puzzle remains valid. If the solver encounters a contradiction (i.e., an invalid move), it backtracks and tries a different value. This process continues until a solution is found or all possibilities are exhausted.

## Contributing

Contributions are welcome! If you'd like to improve this Sudoku solver or fix any issues, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/NITHES2003/Sudoku_Solver/blob/main/LICENSE.md) file for details.
