---
title: "Reinforcement Learning for the CartPole problem"
excerpt: "I implement a Q-Table and a Deep Q-Network (DQN) to solve the CartPole problem<br/><img src='/images/q_table_training.png' width='50%'>"
collection: projects
---

A presentation can be found [here](https://thomasloux.github.io/files/rl-cartpole.pdf) and code on this [repo](https://github.com/thomasloux/RL_cartpole). This project allowed to concretely implement the theory of Reinforcement Learning and Bellman Equation. 

Using the simple CartPole environment, I compare several algorithms to solve the problem, from rule-based implementation to Q-Table and Deep Q-Network (DQN). The Q-Table achieves a score of 250 on average, while the DQN achieves a score of 100 at most, facing convergence issues. Other models such as the Actor-Critic algorithm could be implemented to solve the problem, allowing for a more stable convergence for the policy and value function approximated by the neural network.

<img src='/images/q_table_training.png' width='50%'>
