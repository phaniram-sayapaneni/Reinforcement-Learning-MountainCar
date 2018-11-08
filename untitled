# Deep-Reinforcement-Learning-Q Network

Game configurations:
Demon Attack

The agent needs too move around and attack the demons.
Action space: 6

Observations: Image pixel values
Each observation is a concatenation of 4 consecutive frames

Reward: given by the API
Done: if the game is completed

RL algorithms used:
Q learning algorithm

Input: Raw pixels from the atari game.

Modelling part:
The vision problem has been solved by applying a convolutional neural network

The RL algorithm applied here is: Q Learning
Q(s,a) = E [reward(st+1,at+1)|st at]
Where Q represents the expected future reward, given the current state, action pair.
The deep neural network next to CNN abstracts this Q function.

Poilcy: To pick action which as highest Q value.

Interaction:
Make random actions initially to fill the experience replay buffer and then learn from these experiences.

Number of episodes played: 10

![Watch the video](https://github.com/phaniram-sayapaneni/Deep-Reinforcement-Learning-Demon-Attack/blob/master/episode-2.gif)