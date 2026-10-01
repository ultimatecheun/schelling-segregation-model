# Schelling Segregation Model

An agent-based simulation of **Thomas Schelling's model of segregation** in Python — a classic demonstration of how mild individual preferences can cascade into large-scale emergent patterns. Built as a computational-modeling project.

## Overview

Agents of two types live on a grid. Each agent is "happy" when a threshold fraction of its neighbors/friends are of its own type; unhappy agents relocate. Even with modest tolerance thresholds, the population self-organizes into strongly segregated clusters — the model's famous, counterintuitive result.

## What's inside

| File | Purpose |
|------|---------|
| `HW2SchellingFullCodes.ipynb` | Full notebook (recommended — run cell by cell) |
| `hw2schellingfullcodes.py` | Script version of the same model |

The code defines an `Agent` class and an environment (grid, population, occupancy), applies a move policy for unhappy agents, and visualizes the evolving configuration over iterations.

## Run it

Easiest in **Google Colab** or Jupyter — open the notebook and run each cell, adjusting parameters (grid size, population mix, tolerance, number of friends) as you go.

```bash
python hw2schellingfullcodes.py
```

## Requirements

Python 3 with `numpy` and `matplotlib`.

## Author

**Oluwaseun A. Adekoya** — Robotics Engineer & PhD Candidate, University of Cincinnati. License: MIT.
