# Reinforcement_learning
This is the 4th project of EECS 738. We consider a game environment, and formulate ideas on how to use Reinforcement learning. I have use the Gym library to visualize a taxi driver environment with passenger pick up points and drop-off point. The goal will be to make the drive pick up the passenger and drop of at the required location all by using the optimal path. 

# Implementation.
I have implemented a Markov Decision Process. It consist of an environment, agent, states, reward, policy and discount factor. The environment provides the agent with a reward for being in a state and taking an action. The goal of the process is to maximize the rewards. There will be negative rewards for incorrect actions. The rewards are a motivator for the agent and helps it learn and make correct decisions. 

I have implemented policy iteration to find the optimal policy. The environment used deterministic policy. Initial values for states are set to zero and the rewards are calculated using an initial random policy. The updated state values are found using the initial policy, and a new updated policy is formulated using those state values. This process is iterated untill the required policy convergence is achieved. 

# Results

The results of this project are very good and are documented in the jupyter notebook file. The results are better viewed after running the codes. ( git did not do justice to the visuals on the jupyter notebook. The taxi is not visible on the output in git.) 
