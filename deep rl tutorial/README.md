# 👋 Welcome to the Deep Reinforcement Learning Tutorial

Hey there!

Welcome to this Deep Reinforcement Learning (DRL) tutorial!

During my graduate course on neural networks and deep learning at Ferdowsi University of Mashhad, under the guidance of Dr. Rouhani, I was tasked with making a presentation about deep reinforcement learning. It was a fascinating challenge to connect what we learned in class with the real-world applications of deep learning in reinforcement scenarios.

The objective of this tutorial is to take you on the journey I undertook while preparing for a presentation on deep reinforcement learning. My mission was: to connect the dots between the theoretical concepts we learned in class and the cutting-edge applications of deep learning in reinforcement scenarios. Then, I was to select a research paper, decipher its contents, examine its code implementation, and strive to enhance upon it. I decided to share the first part of that journey here.

In this tutorial, I intend to guide you through the fundamental concepts of DRL in a way that is clear and easy to follow. I've done my best to put together a straightforward and coherent tutorial, and I've used insights from various sources, especially Huggingface's [deep RL course](https://simoninithomas.github.io/deep-rl-course/), which shaped the structure of this tutorial. All screenshots/images in these notes credit to that course. Please reach out to me [zahra.niazi@mail.um.ac.ir](mailto:zahra.niazi@mail.um.ac.ir) if you’d like to contribute to these notes!

The slides for this tutorial can be found [here](https://docs.google.com/presentation/d/1R8bK2\_BzFIJtn8VFUzW6BvzrO22wxqUGdT4V-Sfal04/edit?usp=drive\_link)!

{% embed url="https://docs.google.com/presentation/d/1R8bK2_BzFIJtn8VFUzW6BvzrO22wxqUGdT4V-Sfal04/edit?usp=sharing" %}

So, let's get started with Deep Reinforcement Learning!



# Table of contents

* [👋 Welcome to the Deep Reinforcement Learning Tutorial](README.md)

## The Reinforcement Learning Framework

* [The Big Picture](the-reinforcement-learning-framework/the-big-picture/README.md)
  * [RL Process](the-reinforcement-learning-framework/the-big-picture/rl-process.md)
  * [The reward hypothesis](the-reinforcement-learning-framework/the-big-picture/the-reward-hypothesis.md)
* [State/Observation Space](the-reinforcement-learning-framework/state-observation-space.md)
* [Action Space](the-reinforcement-learning-framework/action-space.md)
* [Rewards and discounting](the-reinforcement-learning-framework/rewards-and-discounting.md)
* [Types of Tasks](the-reinforcement-learning-framework/types-of-tasks.md)
* [The Exploration/Exploitation tradeoff](the-reinforcement-learning-framework/the-exploration-exploitation-tradeoff.md)

## Two main approaches for solving RL problems

* [Policy-Based Methods](two-main-approaches-for-solving-rl-problems/policy-based-methods.md)
* [Value-Based Methods](two-main-approaches-for-solving-rl-problems/value-based-methods.md)

## Value-Based Functions

* [State Value Function](value-based-functions/state-value-function.md)
* [Action Value Function](value-based-functions/action-value-function.md)
* [The Bellman Equation](value-based-functions/the-bellman-equation.md)

## Value-Based Learning Strategies

* [Monte Carlo vs Temporal Difference Learning](value-based-learning-strategies/monte-carlo-vs-temporal-difference-learning/README.md)
  * [Monte Carlo: learning at the end of the episode](value-based-learning-strategies/monte-carlo-vs-temporal-difference-learning/monte-carlo-learning-at-the-end-of-the-episode.md)
  * [Temporal Difference Learning: learning at each step](value-based-learning-strategies/monte-carlo-vs-temporal-difference-learning/temporal-difference-learning-learning-at-each-step.md)
  * [Summary](value-based-learning-strategies/monte-carlo-vs-temporal-difference-learning/summary.md)
* [Off-policy vs On-policy](value-based-learning-strategies/off-policy-vs-on-policy.md)
* [Q-Learning](value-based-learning-strategies/q-learning/README.md)
  * [Introducing Q-Learning](value-based-learning-strategies/q-learning/introducing-q-learning.md)
  * [The Q-Learning Algorithm](value-based-learning-strategies/q-learning/the-q-learning-algorithm.md)

## Deep Q-Learning

* [From Q-Learning to Deep Q-Learning](deep-q-learning/from-q-learning-to-deep-q-learning.md)
* [The Deep Q-Network (DQN)](deep-q-learning/the-deep-q-network-dqn.md)
* [The Deep Q-Learning Algorithm](deep-q-learning/the-deep-q-learning-algorithm/README.md)
  * [Experience Replay](deep-q-learning/the-deep-q-learning-algorithm/experience-replay.md)
  * [Fixed Q-Target](deep-q-learning/the-deep-q-learning-algorithm/fixed-q-target.md)
  * [Double DQN](deep-q-learning/the-deep-q-learning-algorithm/double-dqn.md)

## Policy-Based Learning Strategies

* [Introducing Policy-Gradient Methods](policy-based-learning-strategies/introducing-policy-gradient-methods.md)
* [The Advantages and Disadvantages of Policy-Gradient Methods](policy-based-learning-strategies/the-advantages-and-disadvantages-of-policy-gradient-methods.md)
* [Policy-Gradient Methods](policy-based-learning-strategies/policy-gradient-methods/README.md)
  * [The Policy-Gradient Theorem](policy-based-learning-strategies/policy-gradient-methods/the-policy-gradient-theorem.md)
* [The Reinforce Algorithm](policy-based-learning-strategies/the-reinforce-algorithm/README.md)
  * [The Problem of Variance in Reinforce](policy-based-learning-strategies/the-reinforce-algorithm/the-problem-of-variance-in-reinforce.md)

## Actor-Critic Methods

* [Introducing Actor-Critic Methods](actor-critic-methods/introducing-actor-critic-methods.md)
* [The Actor-Critic Process](actor-critic-methods/the-actor-critic-process.md)
* [Adding Advantage in Actor-Critic (A2C)](actor-critic-methods/adding-advantage-in-actor-critic-a2c.md)

## Offline Reinforcement Learning

* [Offline vs. Online Reinforcement Learning](offline-reinforcement-learning/offline-vs.-online-reinforcement-learning.md)
* [What makes Offline Reinforcement Learning Difficult?](offline-reinforcement-learning/what-makes-offline-reinforcement-learning-difficult.md)

