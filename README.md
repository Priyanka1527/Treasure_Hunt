# Treasure Hunters Inc.

Submitted by: Priyanka Saha

EECS 738 Project - The goal of this project is to implement a treasure hunt game to find the optimal path to treasure using Reinforcement learning.

## We do the treasure hunting and monster fighting for you

1. Set up a new git repository in your GitHub account
2. Think up a map-like environment with treasure, obstacles and opponents
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how reinforcement learning can be used to find treasure efficiently while avoiding obstacles and opponents
5. Build one or more reinforcement policies to model situational assessments, actions and rewards programmatically
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub

## Usage of Reinforcement learning on treasure hunt:

Reinforcement learning is the science of making optimal decisions. It works using the concept of agent who wants to perform a task, reward system to help the agent evaluate different scenarios, an environment where the tasks needed to be performed and different states to make transition/take an action. Hence, if we consider an user/warrior to be the agent who wants to reach to the treasure, then in each state on its path would be evaluated using rewards. The agent will achieve more reward for an obstacle free state and for certain actions avoiding opponents on its way to the goal state. The agent needs to be trained multiple times in order to be able to learn all the state-actions, dangers and rewards on its way. In other words, we need to train the model performing multiple iterations until the agent has done trying all the possible state-actions pairs. Now, finally the output will be considered in order to trace out the optimal path to find the treasure or to reach to the goal state.

## Implementation of Reinforcement algorithm for treasure hunt:

The details of implementation including all the policies to model situational assesments, actions and rewards have been documented in the notebook **Treasure Hunt - Reinforcement Learning.ipynb** which is self-contained. The final result showing the optimal path can be found in the notebook as well.

## Observations and future work:

The change in the reward values were noticable with the change of discount factor. We've used 0.8 in this assignment. Also, it would be good to explore the actual image modification using the results obtained from the model.

## References:
https://www.geeksforgeeks.org/what-is-reinforcement-learning/
https://towardsdatascience.com/reinforcement-learning-with-python-8ef0242a2fa2
https://medium.freecodecamp.org/an-introduction-to-q-learning-reinforcement-learning-14ac0b4493cc

