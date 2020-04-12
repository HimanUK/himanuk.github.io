---
title: "Reinforcement Learning: Motivation"
date: 2020-04-12
excerpt: "Machine learning, 3 parts, recent successes, etc."
tags: [Reinforcement Learning]
mathjax: "true"
comments: "true"
---

## Where does RL fit into Machine Learning?

Machine Learning(ML) techniques enable the computer to learn from data/experience without being explicitly programmed to do so. It crudely encompasses 3 parts:
* Supervised Learning - The algorithm usually assumes a model to learn and labelled historical data. The data is used to tune the parameters of the model so that the model can mimic the historical performance given novel data.
* Unsupervised Learning - Works with unlabelled data. It tries to find patterns in the given data.  
* Reinforcment Learning - Works with a simulator where a data point can be sampled at will. Uses scalar signals as feedback to improve the performance. 

## Intuition 

As the name suggests, Reinforcement Learning(RL) is about learning to do a task with reinforcements. Imagine a kid learning to ride a bicycle. Nobody explicitly instructs the kid to apply say 5kN of force on the pedal, maintain your body balance on either sides of the centre of gravity, etc. Instead, he is made to ride it. While riding he may fall down and hurt himself(negative reinforcement) or he may ride it just fine and gain the appreciation(positive reinforcement) from his parents. Essetially, the kid uses trial and error approach and uses reinforcements to makesmall changes in the way he rides and finally learns it. RL techniques attempt to encode this basic way of human learning into algorithms.

## Few recent applications

## Formal

Formally, RL is a sequential decision making framework wherein an agent learns the mapping from situations to actions 

## Highlighting the uniqueness

RL in my opinion, is more generalized than supervised or unsupervised learning.

In Supervised learning, one uses the notion of a loss function to correct the model parameters whereas we use reward signals to accomplish the same task in RL. When one uses the notion of a loss function, one not only knows what direction the optimal result lies but also has a crude idea of how far it is. In a generic RL setting we are deviod of that distance information. A good RL algorithm is capable of learning with {+1,-1} reward signals.

In Supervised and Unsupervised learning, finite data points are provided to run the algorithm. Whatever the algorithm has to accomplish is to be done using the given data. Additionally, one does not have any control on the data. However, RL we have a simulator. We can get as many data points as we need but the aim is to learn using as few data points as possible. Also, in a few settings, RL enjoys the luxury of sampling the data points anywhere in the input space.  As a result, one faces a dilemma between sampling more data points from a region to improve its understanding or explore other regions. Crudely, this is known as the exploration-exploitation tradeoff.


