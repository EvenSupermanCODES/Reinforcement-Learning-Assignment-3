# Reinforcement Learning Assignment 3

## Table of Contents
- [Contributors](#contributors)
- [Overview](#overview)
- [Environments and Algorithms Implemented](#environments-and-algorithms-implemented)
- [Results](#results)
- [Setup and Reproduction Guide](#setup-and-reproduction-guide)
- [Contact](#contact)

## Contributors
- **Chowdhury Nafis Saleh**
  - ID: 202381888
- **Md Jawad Khan**
  - ID: 202381977

## Overview
This repository contains our work on two reinforcement learning problems for the Assignment 3 : Grid World Navigation (Part 1 of Assignment 3) and Random Walk on a 7x7 Grid (Part 2 of Assignment 3). We implemented and analyzed various reinforcement learning algorithms, including SARSA, Q-learning, Gradient Monte Carlo, and Semi-gradient TD(0).

## Environments and Algorithms Implemented

1. Grid World Navigation (5x5 grid) (Part 1 of Assignment 3):
   - SARSA
   - Q-learning

2. Random Walk on 7x7 Grid (Part 2 of Assignment 3):
   - Gradient Monte Carlo
   - Semi-gradient TD(0) with affine function approximation

## Results
**Please Refer to the report (sent as Email Attachment) for full results and analysis**

### Grid World Navigation (Part 1 of Assignment 3)
- Implemented SARSA and Q-learning algorithms
- Analyzed trajectories and sum of rewards over episodes
- Compared the performance and characteristics of both algorithms

### Random Walk on 7x7 Grid (Part 2 of Assignment 3)
- Implemented Gradient Monte Carlo and Semi-gradient TD(0)
- Compared value function approximations with the exact value function
- Analyzed mean squared errors and maximum absolute errors

Please note, detailed results, including trajectory analysis, reward plots, and value function heatmaps, are available in the report (which was sent as attachment) and alos Google Colab contains the codes.

## Setup and Reproduction Guide

### Option 1: Google Colab (Recommended)
1. Access the notebook via this link: [RL Assignment 3 {Submitted}.ipynb](https://colab.research.google.com/drive/1UL-CDnxQDYy2XZoIQ5e2Be8nzu36O-ZH?usp=sharing)
2. Run the cells in the notebook to reproduce the results

### Option 2: Local Setup
#### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required libraries: numpy, matplotlib, tqdm

#### Installation
1. Clone the repository:
   git clone [repository-link]
2. Install the required libraries:
   pip install numpy matplotlib tqdm

#### Execution
1. Navigate to the repository's directory:
   cd [repository-name]
2. Start Jupyter Lab:
   jupyter lab
3. Open the `RL Assignment 3 {Submitted}.ipynb` file and execute the cells to see the code and results.

### Note on Reproducibility
Due to the stochastic nature of the algorithms, exact numerical results may vary slightly between runs, but overall trends and conclusions should remain consistent.

## Contact
For any questions or clarifications, please contact:
- Chowdhury Nafis Saleh - cnafissaleh@mun.ca
- Md Jawad Khan - mjawadk@mun.ca
