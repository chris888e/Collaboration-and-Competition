# Collaboration and Competition

This repository contains a solution for the Unity "Tennis" environment. This environment is a rough simulation of the actual game of tennis. There are two players, or "agents", each of which controls a racket. The agents each receive a reward of +.1 for hitting the ball over the net, but get a negative reward (-.01) if the ball touches the ground or falls out of bounds. The environment is considered solved when an average score of +0.5 over 100 consecutive episodes (after taking the maximum over both agents) is achieved.

The code trains the agents using an algorithm known as Deep Deterministic Policy Gradients (DDPG). This is an "actor-critic" algorithm that employs two neural networks, one for the actor, the other for the critic. Each of the two agents used on the solution to the environment has its own actor and critic network, however, there is a shared memory buffer from which each agent draws "experiences". Here, experiences are stored observations from the environment.


## Dependencies

Set up a python environment and download the Unity environment by following steps 1 and 2 of the instructions <a href="https://classroom.udacity.com/nanodegrees/nd893/parts/ec710e48-f1c5-4f1c-82de-39955d168eaa/modules/89b85bd0-0add-4548-bce9-3747eb099e60/lessons/3cf5c0c4-e837-4fe6-8071-489dcdb3ab3e/concepts/e85db55c-5f55-4f54-9b2b-d523569d9276">here</a>.

## Installation

To run the DDPG solution code, download the following files and place them in the same directory:
    
    Continuous_Control.ipynb
    dqn_agent.py
    model.py

The code can then be run by opening the Collaboration and Competition notebook in the prescribed environment and running the cells.

