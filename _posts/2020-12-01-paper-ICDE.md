---
title: "Accepted paper at ICDE 2021"
date: 2020-12-02T00:00:00-00:00
categories:
  - paper
---

Our paper entitled ["An Actor-Critic Ensemble Aggregation Model for Time-Series Forecasting"](/assets/publications/ICDE21.pdf) has been accepted at the [37th International Conference on Data Engineering (ICDE)](https://icde2023.ics.uci.edu/) as a poster.

### Abstract
Ensemble models are widely used as an effective technique in time-series forecasting, and recently, are inclined toward leveraging meta-learning methods due to their proven predictive advantages in combining individual models in an ensemble. However, finding the optimal strategy for ensemble aggregation is an open research question, particularly, when the ensemble needs to be adapted in real-time. In this paper, we pro-pose a novel meta-learning approach for aggregation of linearly weighted ensembles for the task of time-series forecasting. We outline a deep reinforcement learning framework with a coherent design of the components of the environment and the objective function as an aggregation method in our task. In this framework, the combination policy in ensembles is modeled as a sequential decision making process which is able to capture the temporal behavior in time-series, and an actor-critic model aims at learning the optimal weights in a continuous action space. An extensive empirical study on various real-world datasets demonstrates that our method achieves excellent or on par results in comparison to the state-of-the-art approaches as well as several baselines.