<<<<<<< HEAD
## Ehsan Arabnezhad

# Continuous Control 

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

## Getting started

1. Download the environment from one of the links below. You need to only select the environment that matches your operating sytem:
   - Version 1: One (1) Agent 
     - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
     - Max OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
     - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
     - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
 
   - Version 2: Twenty (20) Agents
     - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
     - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
     - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
     - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
     
 (*For Windows users*) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.
 
 (*For AWS*) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), the please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

## Dependencies
1. Python 3.6
2. Pytorch
3. Unity ML-Agents

## How to run the agent
To start training, simply open *Continuous_Control.ipynb* in Jupyter Notebook and follow the instructions there:

Start Jupyter Notebook
```bash
jupyter notebook
```
Trained model weights is included for quickly running the agent and seeing the result in Unity ML Agent.
Simply skip the training step and run the last step of the *Continuous_Control.ipynb*
||||||| merged common ancestors
=======
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
>>>>>>> 8f4d884dc871f372944bfa0bbd7f07d9cf74d518
