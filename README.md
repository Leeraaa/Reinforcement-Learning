# Reinforcement-Learning

# Deep Reinforcement Learning: DQN vs PPO on LunarLander-v3

## Overview

This project was developed as part of the Reinforcement Learning course at HIT (Holon Institute of Technology).

The goal of the project is to train autonomous agents to solve the LunarLander-v3 environment using two popular Deep Reinforcement Learning algorithms:

* Deep Q-Network (DQN)
* Actor-Critic (PPO-style Policy Optimization)

The project provides a complete implementation, training pipeline, evaluation framework, and comparative analysis of both approaches.

---

## Problem Description

The LunarLander-v3 environment simulates the task of safely landing a spacecraft on a designated landing pad.

The agent must learn how to:

* Control the main engine
* Control side thrusters
* Stabilize the spacecraft
* Reduce landing velocity
* Land accurately without crashing

The environment contains:

* 8-dimensional state space
* 4 discrete actions

The objective is to maximize cumulative reward while achieving a safe landing.

---

## Algorithms Implemented

### Deep Q-Network (DQN)

The DQN implementation includes:

* Deep Neural Network Q-function approximation
* Experience Replay Buffer
* Target Network
* Bellman Equation Updates
* ε-Greedy Exploration Strategy

Key components:

* Replay Memory
* Mini-batch Training
* Target Network Synchronization
* Reward Tracking
* Performance Evaluation

---

### Actor-Critic (PPO-style)

The Actor-Critic implementation includes:

* Actor Network
* Critic Network
* Policy Gradient Learning
* Advantage Estimation
* Policy Optimization

The Actor learns the optimal policy while the Critic estimates state values and guides policy improvement.

---

## Project Workflow

### 1. Environment Initialization

* LunarLander-v3
* Reproducible random seeds
* Training and evaluation environments

### 2. Agent Design

* Neural network architectures
* Action selection strategies
* Value estimation

### 3. Training

For each algorithm:

* State observation
* Action selection
* Environment interaction
* Reward collection
* Parameter updates

### 4. Evaluation

Performance is measured using:

* Episode reward
* Episode length
* Convergence speed
* Stability

### 5. Visualization

The project includes:

* Training curves
* Moving averages
* Reward distributions
* Agent gameplay recordings

---

## Technologies Used

* Python
* PyTorch
* Gymnasium
* NumPy
* Pandas
* Matplotlib
* MoviePy
* Google Colab

---

## Experimental Results

### DQN

Characteristics:

* Higher peak reward
* Strong final performance
* Slower convergence

---

### Actor-Critic (PPO)

Characteristics:

* Faster convergence
* More stable learning
* Lower variance

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Reinforcement Learning
* Deep Reinforcement Learning
* Deep Q-Networks (DQN)
* Actor-Critic Methods
* Policy Optimization
* Neural Networks
* PyTorch
* Markov Decision Processes
* Agent Training
* Performance Evaluation
* Scientific Programming

---

## Repository Contents

* Complete implementation
* Training and evaluation pipeline
* Reward analysis and visualizations
* Agent gameplay recordings

---

## Results

Both reinforcement learning agents successfully learned to solve the LunarLander-v3 environment.

Key achievements:

* Successful autonomous landing
* Stable policy learning
* Comparative analysis of value-based and policy-based methods
* Visualization of agent behavior
* Quantitative evaluation of performance and convergence
