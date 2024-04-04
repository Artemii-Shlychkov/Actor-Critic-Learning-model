# Actor-Critic-Learning-model

## Overview
Here we model a sequential decision problem, where the information about the consequences of animals' actions is not 
necessarily immediately provided. Instead reward is based on the sequence of actions.
### The model
The Actor-Critic method is a fundamental approach in reinforcement learning, a type of machine learning where an agent 
learns to make decisions by interacting with an environment. It combines two main components: the Actor and the Critic, 
each with a distinct role in learning optimal behavior. The Actor is responsible for making decisions or selecting actions based 
on the current state of the environment. It essentially maps states to actions, 
trying to choose actions that will maximize future rewards. The Actor's policy is updated based on feedback from the Critic, 
which evaluates the actions taken.
The Critic evaluates the actions taken by the Actor by estimating the value function, which is a prediction of future rewards. 
The value function helps in assessing how good a particular state is for an agent. 
The Critic's feedback to the Actor is crucial for learning, as it helps the Actor adjust its policy towards more rewarding actions.
In the Actor-Critic method, both the Actor and the Critic are updated iteratively based on their performance. The Critic's evaluation 
helps to adjust the Actor's policy parameters through a learning process, often implemented using methods like Temporal 
Difference (TD) learning. The Actor's role is to adjust its policy to increase the expected future rewards, guided by 
the Critic's value function.

## Structure

1. Environment and Dependencies Setup
2. Simulation of the model, given different parameters
3. Vizualisation of the results
4. Conclusion

## Conclusion

The Jupyter notebook provides a comprehensive guide to understanding and implementing an Actor-critic model in reinforcement learning, 
with theoretical explanations complemented by practical code examples. This notebook provides both conceptual explanations and hands-on programming 
experience.
