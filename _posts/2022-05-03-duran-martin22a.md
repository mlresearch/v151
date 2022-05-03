---
title: " Efficient Online Bayesian Inference for Neural Bandits "
abstract: " In this paper we present a new algorithm for online (sequential) inference
  in Bayesian neural networks, and show its suitability for tackling contextual bandit
  problems. The key idea is to combine the extended Kalman filter (which locally linearizes
  the likelihood function at each time step) with a (learned or random) low-dimensional
  affine subspace for the parameters; the use of a subspace enables us to scale our
  algorithm to models with $\\sim 1M$ parameters. While most other neural bandit methods
  need to store the entire past dataset in order to avoid the problem of “catastrophic
  forgetting”, our approach uses constant memory. This is possible because we represent
  uncertainty about all the parameters in the model, not just the final linear layer.
  We show good results on the “Deep Bayesian Bandit Showdown” benchmark, as well as
  MNIST and a recommender system. "
software: " https://github.com/probml/bandits "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: duran-martin22a
month: 0
tex_title: " Efficient Online Bayesian Inference for Neural Bandits "
firstpage: 6002
lastpage: 6021
page: 6002-6021
order: 6002
cycles: false
bibtex_author: Duran-Martin, Gerardo and Kara, Aleyna and Murphy, Kevin
author:
- given: Gerardo
  family: Duran-Martin
- given: Aleyna
  family: Kara
- given: Kevin
  family: Murphy
date: 2022-05-03
address:
container-title: Proceedings of The 25th International Conference on Artificial Intelligence
  and Statistics
volume: '151'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 5
  - 3
pdf: https://proceedings.mlr.press/v151/duran-martin22a/duran-martin22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
