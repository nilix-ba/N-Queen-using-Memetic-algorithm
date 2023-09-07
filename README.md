# N-Queen using Memetic Algorithm

## Introduction
This Python script implements a Memetic Algorithm to solve the N-Queens problem, where N queens must be placed on an N×N chessboard such that no two queens threaten each other.

## Dependencies
- numpy
- pandas
- more_itertools
- matplotlib

## Description
- `fitness_func(chromosome)`: Calculates the fitness of a chromosome by counting the number of queen threats.
- `local_search(chromosome)`: Performs local search on a chromosome to improve its fitness.
- `society_creator(population)`: Creates a population of chromosomes with random queen placements.
- `truncation(T, N)`: Selects the top N chromosomes from the population based on truncation selection with parameter T.
- `crossover(gene1, gene2)`: Performs crossover between two chromosomes to create a child chromosome.
- `mutation(gene)`: Applies mutation to a chromosome.
- The script iteratively evolves the population using the Memetic Algorithm until a solution is found.

## Results
The script outputs the best solution found, which is a placement of N queens on the chessboard without threatening each other.
