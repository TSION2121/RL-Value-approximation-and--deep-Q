
# Lab 4 – Monte Carlo vs Deep Q-Learning

This repository contains **Lab 4** for a Reinforcement Learning course.  
The lab compares **Monte Carlo control with linear function approximation** and **Deep Q-Learning (DQL)** in a simple 1D continuous-state environment with discrete actions.

## path to the report:  report/RL lab 4.pdf


## Summary
- Monte Carlo control uses polynomial feature-based linear approximation.
- Deep Q-Learning uses a neural network, experience replay, and a target network.
- In this environment, Monte Carlo converges faster, is more stable, and achieves better performance than DQL.

## Files
- `RL_Lab4.ipynb` – Implementation, experiments, and visualizations
- `README.md` – Project description

## Key Takeaway
For simple, low-dimensional environments, **linear function approximation can outperform deep reinforcement learning methods**, which are more sensitive to hyperparameters and computationally expensive.


