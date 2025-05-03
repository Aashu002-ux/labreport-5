# labreport-5

#  N-Queens Problem Solver using Genetic Algorithms

This project provides a Python implementation of the **N-Queens problem** solved using a **Genetic Algorithm (GA)**. The goal is to place N queens on an N × N chessboard such that no two queens threaten each other.



## Objective

To apply Genetic Algorithms to find valid solutions to the N-Queens problem by simulating the principles of natural evolution—selection, crossover, and mutation.



## How It Works

- **Chromosome Representation:** Each chromosome is a list of N integers, where each value represents the row position of a queen in its respective column.
- **Fitness Function:** Counts the number of non-attacking queen pairs. The maximum possible fitness is `N*(N-1)/2`.
- **Selection:** Tournament selection is used to choose parents based on fitness.
- **Crossover:** A single-point crossover combines two parents to create an offspring.
- **Mutation:** With a small probability, a random queen's position is changed.





