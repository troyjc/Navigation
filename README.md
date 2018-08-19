# Navigation
Project #1 for Udacity Deep Reinforcement Learning course.

## Project Details

The state space has 37 dimensions and contains the agent’s velocity, along with ray-based perception of objects around the agent’s forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to
- **0** - move forward
- **1** - move backward
- **2** - turn left
- **3** - turn right.

The task is episodic: in order to solve the environment the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started
To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

        - __Linux__ or __Mac__:
        ```bash
        conda create --name drlnd python=3.6
        source activate drlnd
        ```
        - __Windows__:
        ```bash
        conda create --name drlnd python=3.6
        activate drlnd
        ```

2. Clone the repository and navigate to the `python/` folder.  Then, install several dependencies.
```bash
git clone https://github.com/udacity/deep-reinforcement-learning.git
cd deep-reinforcement-learning/python
pip install .
```

This will install PyTorch and Unity ML-Agents.

## Instructions
Running the code in the repository and training the agent is straightforward. The `Navigation.ipynb` Jupyter notebook should be used to run the code in the repository and train the agent.
