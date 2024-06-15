# Reinforcement Learning Agent: Cliff Walking

This project focuses on developing a Reinforcement Learning (RL) agent to find a safe route in a dynamic cliff walking environment. The primary objective is to minimize the number of steps required to reach the end state while adapting to dynamic changes in the environment.

## Project Overview

The RL agent is designed to navigate through a grid world, avoiding cliffs and finding the optimal path to the goal. The agent's learning progress is visualized through cumulative reward plots, providing insights into its performance over time.

## Key Features

- **Dynamic Environment**: Configurable parameters such as learning rate, discount factor, and training episodes.
- **Visualization**: Real-time plots of average rewards per episode and cumulative rewards.
- **Performance Analysis**: Evaluation of factors such as speed, learning stability, and policy effectiveness.

## Input Modules

- **Dynamic Environment Parameters**: Configurable settings for the cliff walking environment.
- **Hyperparameters**: Adjustable parameters such as learning rate and discount factor.
- **Training Episodes**: Number of episodes for training the RL agent.

## Output Modules

- **Average Rewards per Episode**: Average reward obtained in each training episode.
- **Cumulative Reward**: Total reward accumulated over all episodes.
- **Agent’s Policy**: The strategy developed by the agent to maximize rewards.
- **Performance Analysis**: Metrics such as speed, learning stability, and effectiveness.

## Technology Stack

- **OpenAI Gym**: Interface between RL environment and Q-learning algorithm for consistent evaluation.
- **Matplotlib**: Dynamic visualization of average and cumulative rewards.
- **Python Standard Library**: Supports functionalities like file I/O, logging, maintainability, and code organization.

## Hardware Requirements

- Multi-core 2.0 GHz processor
- 8 GB RAM
- 100 GB storage
- Optional GPU with CUDA support (4 GB VRAM) for handling complex RL tasks efficiently

## Software Requirements

- Python 3.6 or higher
- Libraries: OpenAI Gym, NumPy, Matplotlib
- Package Manager: pip or conda for managing dependencies

Find the copy of the complete report [here](/Cliff_Walking_Report.pdf) for reference.
