---
title: Residual Policy Learning for self-driving robot
layout: post
date-made: Autumn 2019
tag: 
- rl
- cv
- pytorch
- ros
headerImage: true
projects: true
hidden: false
description:
category: machinelearning
author: philippemarcotte
externalLink: https://github.com/PhilippeMarcotte/challenge-aido_LF-baseline-duckietown
order: 1
---

For a robotic class named [Duckietown](https://www.duckietown.org/research/ai-driving-olympics), we had robots using a camera to follow a road in a model city. The goal was to  improve the existing system. We used a Pure Pursuit controller as a basis but refined it using [Residual Policy Learning](https://arxiv.org/abs/1812.06298). Instead of modelizing the whole system using Reinforcement Learning, we modeled only a correction that would be applied on top of the PID controller as to make it better. To achieve this, we adapted [https://arxiv.org/abs/1509.02971](DDPG) and used a variety of pretraining. The markdown report can be found [here](https://github.com/PhilippeMarcotte/docs-AIDO/blob/master19/book/AIDO/31_task_embodied_strategies/40_rpl_baseline.md).
