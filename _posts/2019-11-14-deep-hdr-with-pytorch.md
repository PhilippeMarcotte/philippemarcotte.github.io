---
title: Deep HDR with pytorch
layout: post
date-made: Autumn 2017
tag: 
- cv
- supervised
- pytorch
headerImage: true
projects: true
hidden: false
description: Deep HDR with Pytorch project presentation
category: machinelearning
author: philippemarcotte
externalLink: https://github.com/PhilippeMarcotte/Deep-HDR-with-Pytorch
order: 3
---

The project consisted in reproducing the exiperiment describe in this [paper](http://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/) from 
Kalantari, Nima Khademi and Ramamoorthi, Ravi. The experiment consisted in fusing three ordinary images (Low Dynamic Range) of different exposition time from the same scene in one HDR image. For this reason, an optic flow algorithm was used to align the lowest and highest exposition on the normal exposition image. Then, a convolutional network of 4 layers was used to model the fusing process. The report can be found on the github repo.