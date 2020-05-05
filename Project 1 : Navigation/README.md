# Deep Reinforcement Learning Project: Navigation

This repository presents my solution for the [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)'s first project **`Navigation`**. 

### Introduction (Project Details) 

For this project, the goal is to train an agent to navigate (and collect bananas!) in a large, square world. In particular, the agent has to collect as many yellow bananas as possible while avoiding blue bananas. 

![Trained Agent](images/Bananas_way.gif)

For each yellow banana collected the agent gets a reward of +1, and for each blue banana collected the agent gets a reward (which is a penality in this case) of -1.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, that means each episode has a defined end. For this environment, the challenge is to train an agent that gets an average score of +13 over 100 consecutive episodes.

### Getting Started

This project environment is similar to, but not identical to the [Banana Collector](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector) environment on the [Unity ML-agents GitHub page](https://github.com/Unity-Technologies/ml-agents). Thus, to prepare this environment provided by Udacity we need to follow these steps:

1. Configure a Python 3.6 / PyTorch 0.4 environment with the needed requirements as described in the [Udacity repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)

2. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. After cloning the DRLND GitHub repository in your local/working machine, place the file in in the `p1_navigation/` folder of the cloned repository, and unzip (or decompress) the file. 

### Training the agent (Instructions) 

The `Navigation.ipynb` notebook provide instructions on how to train our agent, along with the trained model weights.

This agent has been trained in the online workspace provided by Udacity. While it is possible to observe the trained agent's interaction with the environment, this feature is not yet available. 

