# Udacity-Deep-Reinforcement-Learning-p1-Navigation
DQN implementation for an agent to navigate and collect Bananas

## The problem description

**Environment:** Train an agent to navigate (and collect bananas!) in a large, square world. The environment is based on [Unity ML-agents](https://github.com/Unity-Technologies/ml-agents). 

**Note:** The Unity ML-Agent team frequently releases updated versions of their environment. We are using the v0.4 interface. The project environment provided by Udacity is similar to, but not identical to the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment on the Unity ML-Agents GitHub page.

**The observation space**: The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
**The action space**: the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward.
* 1 - move backward.
* 2 - turn left.
* 3 - turn right.

**Reward:** A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

**Task (Episodic/Continuous):** The task is episodic.

**Solution:** In order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes. 
There are 2 ways to solve this environment- 
1. Learn using state space values such as velocity along with ray based perception of objects around the forward direction.
2. Learn using pixels for the state space.

The Navigation.ipynb solves the first version.

## Getting started

### Installation requirements

- To begin with, you need to configure a Python 3.6 / PyTorch 0.4.0 environment with the requirements described in [Udacity repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)
- Then you need to clone this project and have it accessible in your Python environment
- For this project, you will not need to install Unity. You need to only select the environment that matches your operating system:

    - 
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

        
- Finally, you can unzip the environment archive in the project's environment directory and set the path to the UnityEnvironment in the code.

## Instructions
The configuration for the environement, the agent and the DQN parameters are all in the ipynb file.

