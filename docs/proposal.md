---
layout: default
title:  Proposal
---

## Summary:
The focus of our project is path finding. Our goal is to build an agent that can navigate the environment to find the most efficient path to the reward, or a list of rewards. The agent will process inputs from elements in the environment and all available actions an agent can perform to evaluate possible options. The output would be the optimal sequence of actions to achieve the goal. A possible application is programs for warehouse bots to find and collect items to fullfill a customer's order.

## Evaluation Plan:
### Quantitative Evaluation
Time would be our most important metric, which we would measure in seconds. 
We would want the agent to find the reward in the shortest time possible. 
Distance is another important metric, which can be measured in blocks or meters.
We can use distance to determine if agent can find the most efficient path to 
the goal. Additionally, we also want to keep track of number of moves taken. 
If possible within the time line of the course, we would want to train the agent
to minimize the number of moves taken throught clearing obstacles in the environment
to reveal shortest path. 


### Qualitative Evaluation
The easiest way to determine if our agent is successful in its mission is by seeing if it is able to reach the end goal. First, we will train the agent in a simple environment (with no obstacles) and give multiple rewards along the way until the goal state is reached. Once the agent is able to complete that mission, we will add obstacles to the environment and adjust the rewards accordingly. For example, we can give a higher reward if the agent is able to avoid/break down an obstacle and continue forward.

## Goals:
### Minimum Goal:
- Milestone 1: The agent will be able to navigate a simple environment with no obstacles. 
- Milestone 2: There will be lava on the ground and walls, so the agent will have to find the correct 
path to the reward.

### Realistic Goal:
- Milestone 1: Given multiple paths to the goal, the agent would be above to take 
the most efficient one. 
- Milestone 2: Our agent would achieve efficiency in number of moves take sdflj

### Ambitious Goal:


