---
title: "Reinforcement Learning: Motivation"
date: 2020-04-12
excerpt: "Machine learning, 3 parts, recent successes, etc."
mathjax: "true"
comments: "true"
---

## Where does RL fit into Machine Learning?

Machine Learning(ML) techniques enable the computer to learn from data/experience without being explicitly programmed to do so. It crudely encompasses 3 parts:
* Supervised Learning - The algorithm usually assumes a model to learn and historical data. The data is used to tune the parameters of the model so that the model can mimic the historical performance given novel data. It usually requires labelled data.
* Unsupervised Learning - Works with unlabelled data. It tries to find patterns in the historical data.  
* Reinforcment Learning - Works with a simulator where a data point can be sampled at will. Uses scalar signals as feedback to the algorithms. 

## Intuition

As the name suggests, Reinforcement Learning(RL) is about learning to do a task with reinforcements. Imagine a kid learning to ride a bicycle. Nobody explicitly instructs the kid to apply say 5kN of force on the pedal, maintain your body balance on either sides of the centre of gravity, etc. Instead, he is made to ride it. While riding he may fall down and hurt himself(negative reinforcement) or he may ride it just fine and gain the appreciation(positive reinforcement) from his parents. Using these reinforcements he makes small changes in the way he rides and finally learns it. RL techniques attempt to encode this basic way of human learning into algorithms.

## Highlighting the uniqueness

RL in my opinion, is more generalized than supervised or unsupervised learning.
In supervised learning, one uses the notion of a loss function Reward signals over loss function

