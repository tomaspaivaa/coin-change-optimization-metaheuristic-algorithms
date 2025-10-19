# Coin Change Optimization — Metaheuristic Algorithms in C

A C-based project developed using **CLion**, focused on solving the **Coin Change Problem** through different **metaheuristic optimization algorithms**.  
The goal is to determine the best combination of coins that sums to a target value **V**, using the **minimum number of coins** possible.


## Overview

Given a set of **coin denominations** and a **target value**, the program attempts to find the most efficient combination of coins that exactly matches the target.

Three optimization strategies were implemented and tested:
- **Local Search Algorithm**
- **Evolutionary Algorithm**
- **Hybrid Algorithm** combining both approaches

Each algorithm aims to balance exploration and exploitation to reach near-optimal or optimal solutions efficiently.

## Technologies Used

- **C Language** – Core implementation  
- **CLion (JetBrains)** – Development environment  
- **Excel (Experiências.xlsx)** – Used for analyzing and comparing experimental results  

## Implemented Algorithms

### Local Search
Iteratively explores neighboring solutions to minimize the number of coins used.  
Variants include:
- **Hill Climbing**
- **Simulated Annealing** (accepts worse solutions with a controlled probability)

### Evolutionary Algorithm
A population-based method inspired by biological evolution.  
It uses:
- **Selection**, **Crossover** and **Mutation** operators  
- Fitness evaluation based on solution validity and the number of coins used  

### Hybrid Algorithm
Combines both approaches:
- Starts with an evolutionary algorithm to explore broadly  
- Refines best candidates using local search for faster convergence  

## Experimental Results

All experiments and performance comparisons are documented in [here](/Experiências.xlsx).  
The spreadsheet includes results for:
- Local Search  
- Evolutionary Algorithm  
- Hybrid Algorithm  

Each sheet contains the tested parameters for each file, best results found and average performance metrics.

---

*This work was completed as part of the “Introduction to Artificial Intelligence” course during the 2024/2025 academic year.*



