## Usage

This repository is shared for viewing and evaluation purposes only.

No license is granted for reuse, modification, or distribution of the code.

# Decision-Making RL Model

This project simulates decision-making under uncertainty and fits a simple reinforcement learning model (Q-learning with softmax).

Built as part of my work on decision-making under stress and computational psychiatry.

## What it does
- Simulates behavioral choices across trials
- Estimates learning rate (alpha) and decision sensitivity (beta)
- Visualizes choices and rewards over time

## How to run

pip install -r requirements.txt
python rl_model.py

## Example output
Estimated alpha: ~0.2  
Estimated beta: ~3.0  
Average reward: varies depending on simulation

## Notes
- Higher beta → more deterministic choices  
- Lower beta → more exploratory behavior  
- Alpha controls how quickly the model updates from new information