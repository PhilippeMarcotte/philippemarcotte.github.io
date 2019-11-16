---
title: Deep learning model to detect spelling mistakes
layout: post
date-made: Autumn 2017
tag:
- nlp
- supervised
- pytorch
headerImage: true
projects: true
hidden: true
description:
category: machinelearning
author: philippemarcotte
externalLink: https://github.com/PhilippeMarcotte/SpellCheck_TP4_INF8225
order: 4
---

This project convert the [model made by mkroutikov](https://github.com/mkroutikov/tf-lstm-char-cnn), which was used to predict english words, in order to detect spelling mistakes. The words are converted to an embedding using chatacter-embedding. Then, the embeddings go through a convolutionnal layer and an LSTM.

---