# Continuous Control 

## Ehsan Arabnezhad

## Introduction
This repository contains a Deep Deterministic Policy Gradients (DDPG) agent running in the Unity ML Agent Reacher environment. It can be used to train and evaluate the result of the training.

I use it for the purpose of learning DDPG agent in the context of continuous control of a agent.

The DDPG is implemented in Python 3 using PyTorch.

The report can be found here. (https://github.com/EhsanArabnezhad/Udacity-Multiagent/blob/master/report.pdf)

### Environment
The 3D environment contains 20 double joined arms agents who can move freely to reach the target locations.

### Goal
The goal is to control the 20 arms to move to their individual target locations and keep them there as many time steps as possible.

### Environment Solved Criteria
 The environment is considered solved when the average mean score of all agents reach 30+.
 
### Rewards
A reward of +0.1 is provided for each step that each agent's hand is in the goal location independently.

### Actions
Vector Action space: (Continuous) Size of 4, corresponding to torque applicable to two joints.

### Spaces
The observation space is composed of 33 variables:  
position, rotation, velocity, and angular velocities of the arm


## How to run the agent
To start training, simply open *Continuous_Control.ipynb* in Jupyter Notebook and follow the instructions there:

Start Jupyter Notebook
```bash
jupyter notebook
```
Trained model weights is included for quickly running the agent and seeing the result in Unity ML Agent.
Simply skip the training step and run the last step of the *Continuous_Control.ipynb*
