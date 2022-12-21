# Cart Pole Balancing with DQN
Welcome to the Cart Pole Balancing with DQN repository! This project is a implementation of a deep Q-learning network (DQN) to balance a pole attached to a moving cart.
It was created as part of the Reinforcement Learning module at Imperial College London. This repository also includes the final report, attaining a distinction. 

## Problem Description ##
The goal of this project is to train an agent to balance a pole attached (by a frictionless joint) to a moving (frictionless) cart by applying a fixed force to the cart in either the left or right direction. The aim is to train the DQN to keep the pole balanced (upright) for as many steps as possible. The action space is discrete and of size 2 (left or right). The observation state obtained from the environment is of size 4, consisting of the cart position, cart velocity, pole angle, and pole angular velocity.

The reward is defined as +1 for each step taken, including the final step. The environment terminates when the pole angle exceeds ±12◦, the cart distance from the center exceeds ±2.4, or the number of steps exceeds 500.

## Requirements ##
  - Python 3
  - PyTorch
  - Matplotlib
  - NumPy
  - OpenAI gym

## Features ## 
  - Implementation of a DQN.
  - Implementation of Reinforcement Learning 'tricks', including replay buffer, target network, reward clipping. 
  - Implementation of greedy and epsilon-greedy action selection.
  - Extension of a DDQN.
 
