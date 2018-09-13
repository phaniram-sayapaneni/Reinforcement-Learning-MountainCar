# Reinforcement-Learning-MountainCar

Game configurations:
Mountain Car
The car needs to build the momentum to climb the hill.
Input: move left or right [-1, +1]
Observations: car’s position, car’s velocity
Reward: given by the API
Done: if the game is completed

RL algorithms used:
Policy gradient algorithm

Modelling part:
The policy is modeled as a normal distribution. Whose parameters (mean, variance) were learned to successfully take right actions to finish the game.

Interaction:
Make random perturbations to actions and record the rewards and pick the best policy model.

Number of episodes played: 300

![Watch the video](https://github.com/phaniram-sayapaneni/Reinforcement-Learning-MountainCar/blob/master/MountainCar_game.gif)