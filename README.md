# Ant Colony Optimization (C++)

A C++ implementation of the **Ant Colony Optimization (ACO)** algorithm to solve a simplified **Traveling Salesman Problem (TSP)** using pheromone trails and probabilistic path selection.

---

## Overview

The program simulates ants that explore routes between cities, updating pheromone trails to reinforce shorter paths.  
It demonstrates core ACO mechanisms such as pheromone evaporation, heuristic weighting, and stochastic decision-making.

---

## Parameters

| Parameter | Description | Default |
|------------|--------------|----------|
| `kCities` | Number of cities | 6 |
| `kAnts` | Number of ants | 100 |
| `alpha` | Pheromone influence | 1.0 |
| `beta` | Distance influence | 1.0 |
| `vaporization` | Pheromone evaporation rate | 0.75 |

---

## How to Run

```bash
# Compile
g++ AntColonyOptimization.cpp -o aco

# Run
./aco


## Example Output

