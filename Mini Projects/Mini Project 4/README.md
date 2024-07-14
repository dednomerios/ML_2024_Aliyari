# Mini Project 4: Reinforcement Learning - Wumpus World and Lunar Lander

## Machine Learning Course - K.N.Toosi University

### Instructor: Dr. Aliyari

This mini project is part of the Machine Learning course taught by Dr. Aliyari at K.N.Toosi University. The objective of this project is to implement, evaluate, and visualize reinforcement learning techniques in classic problems like Wumpus World and Lunar Lander.

## Project Description

### Objectives
1. **Reinforcement Learning**: Implement and analyze reinforcement learning algorithms for navigating complex environments.
2. **Wumpus World**: Create an agent to navigate the Wumpus World environment using Q-learning and Deep Q-learning.
3. **Lunar Lander**: Train an agent to solve the Lunar Lander problem using Deep Q-learning.

### Tasks

#### Question 1: Solving Wumpus World
1. **Environment Setup**:
    - Create a 4x4 grid environment with random positions for the agent, gold, Wumpus, and pits.
    - Define actions (move up, down, left, right) and reward structure (e.g., +100 for finding gold, -1000 for falling into a pit, etc.).

2. **Q-learning and Deep Q-learning**:
    - Implement Q-learning and Deep Q-learning algorithms.
    - Train the agent using both methods and compare their performance.
    - Plot cumulative rewards per episode and analyze how the policies improve over time.
    - Discuss the impact of different exploration rates (epsilon) on the learning process.

3. **Policy Comparison**:
    - Compare the efficiency of the learned policies between Q-learning and DQN.
    - Analyze the number of episodes required to find gold consistently without falling into pits.

4. **Network Architecture for DQN**:
    - Describe the neural network architecture used for the DQN agent.
    - Justify the choice of architecture and hyperparameters.

#### Question 2: Deep Q-Learning for Lunar Lander
1. **Lunar Lander Environment**:
    - Study the Lunar Lander environment and summarize its features, action space, and reward system.
    - Implement a DQN agent to solve the Lunar Lander problem.

2. **Training and Evaluation**:
    - Train the agent using different batch sizes (32, 64, 128) and compare their performance.
    - Plot cumulative rewards per episode and select the best-performing batch size.
    - Create a video of the agent's performance at various stages of training (e.g., after 50, 100, 150, 200, 250 episodes).

3. **Model Comparison**:
    - Compare the performance of DQN and Double DQN (DDQN) agents.
    - Plot cumulative rewards and analyze the convergence rates.
    - Create videos showcasing the performance of both models after training.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `scikit-learn`, `tensorflow` or `keras`, `gym`

### Installation

Clone the repository to your local machine:
```bash
git clone https://github.com/dednomerios/ML_2024_Aliyari.git
cd ML_2024_Aliyari/Mini_Project_4

