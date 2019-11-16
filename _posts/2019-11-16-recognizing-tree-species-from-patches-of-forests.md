---
title: Recognizing tree species from patches of forests
layout: post
date-made: Winter 2019
tag: 
- cv
- semi-supervised
- pytorch
headerImage: true
projects: true
hidden: false
description:
category: machinelearning
author: philippemarcotte
externalLink:
order: 2
---

For a project class done during my master, we had to work on three different projects during the semester. The second project I worked on, proposed by Horoma, consisted in having to identify tree species from 21 different ones based on patches of 32x32 pixels that were part of much bigger images of forests. We had only access to a very small labeled dataset and a big unlabeled one. Using Variational and CNN autoencoders, we leverage the unlabeled data to learn differentiating features and create clusters representing each species. Then, using K-mean and the labeled data, we identify each cluster. Finally, our final k-mean model was the best from all the teams working on the project. I was mainly in charge of implementing the training loop for all the models, testing, hyperparameter search and the CNN autoencoder. The code is under NDA.