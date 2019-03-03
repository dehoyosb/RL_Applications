# RL_Applications
Reinforcement Learning Application

In this repository it's shown the usage of a Deep Reinforcement Tecnique called DQN or Deep Q Network, which uses the concepts of Reinforcement Learning applied in a controlled enviroment. Using a Deep Neural Network as a Function Approximator to map state to action pairs, in order to decide how an agent has to act given it's current state and the discounted cummulative reward.

## The Enviroment
The objective of the enviroment is to be used as a playground to train an agent that is capable of traveling through a world picking up yellow bananas and avoiding blue bannanas. Each time the agent picks up a yellow bannana a reward of +1 is provided, and each time the agent picks up a blue bannana a reard of -1 is provided aswell. In this manner, the objective of the agent is to pick up as many yellow bannanas as possible whilst avoiding the blue bannanas.
The enviroment consist of a grid world of 37 states and contains the agents forward velocity, along a ray-based perception of objects around the agents forward direction. Additionally, the agent is only capable of choosing 4 discrete actions: Forward, Backward, turn left and turn right.
The solving this enviroment is an episodic task, and is considered to be solved once the agent reaches and average score during 100 episodes of +13 or more.

## Setting Up Enviroment
Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.

### Step 1: Clone the DRLND Repository
If you haven't already, please follow the [instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

### Step 2: Download the Unity Environment
For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then, place the file in the ```p1_navigation/``` folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.






