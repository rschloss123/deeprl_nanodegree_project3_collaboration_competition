
# Overview  

This project is part of the Multi-Agent Reinforcement Learning course in Udacity's Deep Reinforcement Learning Nanodegree. The goal of this project is to train two reinforcement learning agents in an environment similar to the Unity Tennis environment to play tennis. 

## Environment
Each agent's state is fully observable. The observation/state size is 24 (position and velocity of the ball and racket) and each agent's action size is 2, corresponding to jumping and moving toward/away from the net. 

At each timestep, each agent receives a reward of +0.1 if the agent hits the ball over the net. Each agent receives a reward of -0.1 if the agent hits the ball out of bounds or allows the ball to hit the ground. The aim is to train each agent to select its best action so that the the two agents agent are able to receive an average reward (over 100 episodes) of at least +0.5. For the computation of the average reward, the maximum score between the two agents in a single episode is used.

## Agent
The agent is an implementation of the Deep Determinstic Policy Gradient algorithm that has been modified to accomodate multiple agents in a single environment. Details will be discussed further in the included report.

# Installation

- To set up an Anaconda environment to run this code, you can follow the instructions included [here](https://github.com/udacity/deep-reinforcement-learning#dependencies). These instructions include:

  - Creating a new environment
  - Installing OpenAI gym
  - Cloning Udacity's deep reinforcement learning repository and installing dependencies
  - Creating and running the IPython kernel in the Jupyter notebook that provides the solution to this project. 
- The needed executable (Tennis.exe) for the environment is included in this repository and works for Windows 10 (64 bit).

# Usage
- The solution to this project is provided in the Jupyter notebook (Tennis.ipynb). Run each section of the notebook sequentially to train the agent. 
- To view the details of the the modified DDPG implementation, see model.py and maddpg_agent.py. 
