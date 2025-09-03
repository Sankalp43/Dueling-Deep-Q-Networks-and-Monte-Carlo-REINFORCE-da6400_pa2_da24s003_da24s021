# DA6400: Programming Assignment 2
submitted by 
- Rohit Kumar (DA24S003)
- Sankalp Shrivastava (DA24S021)

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/to1Zk60e)

In this programming assigment, we are supposed to implement two reinforcemnt learning algorithms i.e. Dueling DQN and Monte Carlo REINFORCE. Also, we need to tune hyperparameters. We need to implement two variants of each algorithm and compare these variants with each other.

#### Implementation Details
We have implemented both these algorithms and implementations can be found in respective jupyter notebook present in this github repository. 
- Dueling DQN implementation can be found in `dueling_dqn_implementation.ipynb`
- MC Reinforce implemenation can be found in `mc_reinforce_implementation.ipynb`

We have performed hyperparameter tunning using `wandb` and details/instructions to reproduce can be found in the respective files. In the end, we have used best hyperparameters found from `wandb sweep` to plot the graphs present in the report available in this repository.
