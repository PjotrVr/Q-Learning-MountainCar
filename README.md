## About

Q Learning algorithm performed on MountainCar-v0 gym environment. 

This is relatively simple gym environment.

## Requirements

You'll only need: numpy, matplotlib, pillow and gym.

Exact versions are available in `requirements.txt` file.

You can install those modules in command line/terminal using command: `pip install -r requirements.txt`

## Before training

By doing random actions agent acts like shown below

<img src="./MountainCar Q Learning Before Training Random Movement.gif"/>

## After training

After training for 30,000 iterations we get agent that acts like shown below

<img src="./MountainCar Q Learning After Training REWARD -145.gif"/>

## Training graph

Graph that shows reward over 30,000 iterations can be seen below

As you can see Q-Learning isn't the most stable RL algorithm because it performs horribly when it encounters new state

<img src="./Training Graph.png"/>
