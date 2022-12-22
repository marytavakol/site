---
title: "Accepted paper at ECML Workshop 2019"
date: 2019-07-01T00:00:00-00:00
categories:
  - paper
---

Our paper entitled ["HyperUCB: Hyperparameter Optimization using Contextual Bandits"](/assets/publications/ADS19.pdf) got accepted at [ECML Workshop on Automated Data Science](https://sites.google.com/view/autods).

### Abstract
Setting the optimal hyperparameters of a learning algorithm is a crucial task. Common approaches such as a grid search over the hyperparameter space or randomly sampling hyperparameters require many configurations to be evaluated in order to perform well. Hence, they either yield suboptimal hyperparameter configurations or are expensive in terms of computational resources. As a remedy, Hyperband, an exploratory bandit-based algorithm, introduces an early-stopping strategy to quickly provide competitive configurations given a resource budget which often outperforms Bayesian optimization approaches. However, Hyperband keeps sampling iid configurations for assessment without taking previous evaluations into account. We propose HyperUCB, a UCB extension of Hyperband which assesses the sampled configurations and only evaluates promising samples. We compare our approach on MNIST data against Hyperband and show that we perform better in most cases.

