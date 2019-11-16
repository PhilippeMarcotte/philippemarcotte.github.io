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

The project consisted in reproducing the experiment described in this [paper](http://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/). The experiment consisted in fusing three ordinary images (Low Dynamic Range) of different exposition time from the same scene in one HDR image. For this reason, an optic flow algorithm was used to align the lowest and highest exposition on the normal exposition image. Then, a convolutional network was used to model the fusing process.