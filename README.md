# Reinforcement-Learning---Banana-collector

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.


## Installation

This project is tested under the following environment:
* Anaconda
* Python 3.6
* Window 10 64bits
    

0. As always, Clone Respository before anything else

       conda create --name drlnd python=3.6 
       activate drlnd
       
       git clone https://github.com/udacity/deep-reinforcement-learning.git
       cd deep-reinforcement-learning/python
       pip install .
       
       
