# Ant Colony Optimization (C++)

This project implements the **Ant Colony Optimization (ACO)** algorithm in C++ to solve a simplified **Traveling Salesman Problem (TSP)** using pheromone trails and probabilistic exploration.

---

## Overview

This program simulates how artificial ants cooperatively find near-optimal paths between cities based on:
- Pheromone strength (collective memory of past paths)
- Distance between cities (shorter routes preferred)
- Exploration and evaporation dynamics

Each ant constructs a path through all cities, and pheromone trails are updated to reinforce better routes over time.

---

## Algorithm Highlights

- Ant Colony Optimization for the Traveling Salesman Problem  
- Probabilistic path selection based on pheromone and distance influence  
- Dynamic pheromone update with evaporation and reinforcement  
- Multiple ants exploring the graph simultaneously  

---

## Parameters

| Parameter | Description | Default |
|------------|--------------|----------|
| `kCities` | Number of cities | 6 |
| `kAnts` | Number of ants per iteration | 100 |
| `alpha` | Pheromone importance | 1.0 |
| `beta` | Distance importance | 1.0 |
| `vaporization` | Pheromone evaporation rate | 0.75 |

---

## Example Output

