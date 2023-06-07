Sudoku Solver using Genetic Algorithm
This project implements a Sudoku Solver using a Genetic Algorithm. The Genetic Algorithm is a search and optimization technique inspired by the process of natural selection. It aims to find the best solution (a solved Sudoku grid) by iteratively generating and improving a population of candidate solutions.

How it works
The Sudoku grid is represented as a 9x9 matrix, with empty cells represented by zeros.
The Genetic Algorithm operates on a population of Sudoku solutions, where each solution is a valid arrangement of numbers from 1 to 9 in the grid.
The population is initialized with random solutions that satisfy the rules of Sudoku.
The fitness of each solution is evaluated based on how close it is to being a valid solution. A lower fitness value indicates a better solution.
The Genetic Algorithm proceeds through several steps:
Selection: A subset of solutions is chosen through tournament selection, where the fittest individuals have a higher chance of being selected.
Crossover: Two parent solutions are selected, and a single-point crossover is performed to generate a child solution.
Mutation: A random mutation is introduced in the child solution by swapping two non-steady numbers within a 3x3 region of the grid.
Replacement: The least fit individuals in the population are replaced by the newly generated child solution.
The steps of selection, crossover, and mutation are repeated until a solution with zero fitness (a solved Sudoku grid) is found.
The best solution (solved Sudoku grid) and its fitness value are displayed as the output.
Getting Started
To run the Sudoku Solver:

Type on cmd 

Sudoku_Solver_With_GA


