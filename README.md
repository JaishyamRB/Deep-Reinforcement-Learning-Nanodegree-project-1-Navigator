# Unity Banana Navigation



## Project details

Project created as 1st project on Udacity Deep Reinforcement Learning nanodegree. The goal of the agent is to gather `yellow` bananas while avoiding the `blue` ones. Here are Unity details of the environment:

```
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 
```

That means we work with state vector containing 37 continous values and 4 discrete actions representing moves (forward, backward, turn left, turn right). The environment is considered solved when agents reaches average score of 13.0 on 100 consecutive episodes.

## Getting started

1. Before getting into the project there are certain dependencies to be met. Make sure you have [python 3.6]( https://www.python.org/downloads/release/python-3610/) installed and virtual environment.

2. Unity environment has to be installed on your system 

  - Linux: [here]( https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

  - Mac OSX: [here]( https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

  - Windows (32-bit): [here]( https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

  - Windows (64-bit): [here]( https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip )

3. Download or clone this repo and run these commands in your terminal:

```
pip install requirement.txt
pip -q install ./python
```

4. after installing python dependencies. Then you should be able to run `jupyter notebook` and view `Solution.ipynb`. File `model.py` contains neural network class used as a Q function and file `dqn_agent.py` contains agent code.

## Instructions

Run `Soultion.ipynb` for further details.
