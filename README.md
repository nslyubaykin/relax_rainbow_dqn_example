# Example Rainbow DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_rainbow_dqn_example/blob/master/rainbow_dqn_tutorial.ipynb) of rainbow deep q-network (Rainbow DQN) with ReLAx.

Rainbow DQN actor was trained on MsPacman-v0 Atari Gym environment for 3m env-steps. 
Trained models exceed GitHub's 100mb size limit and may be found [here](https://disk.yandex.ru/d/UNmsM5p-0klVqw).

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![rainbow_dqn_training](https://github.com/nslyubaykin/relax_rainbow_dqn_example/blob/master/rainbow_dqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![rainbow_dqn_q_func](https://github.com/nslyubaykin/relax_rainbow_dqn_example/blob/master/rainbow_dqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187175224-9e6fcd7f-8524-40a0-9346-053c12c48bfe.mp4
