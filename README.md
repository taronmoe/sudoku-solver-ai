# Sudoku Solver: Constraint Satisfaction & Search

This project implements a flexible Sudoku solving framework using multiple
search and constraint satisfaction algorithms. It was developed to explore
algorithmic tradeoffs in deterministic and stochastic problem solving.

## Algorithms Implemented
- Backtracking
- Forward Checking
- Arc Consistency (AC-3)
- Simulated Annealing
- Genetic Algorithm

All algorithms operate under the same constraint-checking interface, enabling
direct comparison.

## Key Design Decisions
- Modular solver architecture with runtime algorithm selection
- Constraint propagation to reduce search space
- Decision-based performance metrics rather than wall-clock timing

## Results
Across tested puzzles, AC-3 consistently provided the best balance of
correctness and search efficiency. Stochastic methods demonstrated learning
behavior but did not reliably solve harder instances.

## Notes
This project was implemented from scratch in Python as part of a personal AI project,
with emphasis on correctness, clarity, and reproducibility.
