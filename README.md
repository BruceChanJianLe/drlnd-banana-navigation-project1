# Deep Reinforcement Learning - Banana Navigation - Project 1

This repository stores the solution to the udacity deep reinforcement learning nanodegree first project which is the banana navigation project.  

## Project Overview

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- `0` - move forward.
- `1` - move backward.
- `2` - turn left.
- `3` - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

Please make sure `python3.6` is installed in your conda environment. Noted that `Unity` has to be installed as well. And run the install script.  

```
source ./install.sh
```

## Running

Please choose your favourite `script` to run. The results are in `report.md`. All the scripts are jupyter notebooks, you will be able to run them with the command `jupyter notebook` and connecting to the server.  

