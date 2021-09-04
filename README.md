Project 1: Navigation
=====================

## Introduction
A solution to banana collector Unity Environment - first project in Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).

## Project details
The task is to train an agent to navigate and collect yellow bananas in a square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

```
Number of actions: 4
States look like:
[ 0.          1.          0.          0.          0.16895212  0.          1.
  0.          0.          0.20073597  1.          0.          0.          0.
  0.12865657  0.          1.          0.          0.          0.14938059
  1.          0.          0.          0.          0.58185619  0.          1.
  0.          0.          0.16089135  0.          1.          0.          0.
  0.31775284  0.          0.        ]
States have length: 37
```

## Getting Started
In order to setup your Python environment, follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning/blob/master/README.md#dependencies). This solution was prepared under Ubuntu 20.04 so take the path for Linux setup.

Apart from Python dependencies, Banana collector unity environment is automatically fetched by the training notebook.

## Instructions
After dependencies and conda environment setup, start jupyter notebook
```
conda activate drlnd
jupyter notebook
```

In jupyter open Navigation.ipynb and select `drlnd` as active kernel.
Run cells up to "4. Train the agent" section if you want to perform training and save model parameters.
Skip section "4. Train the agent" if you want to load pretrained model and evaluate the agent.
