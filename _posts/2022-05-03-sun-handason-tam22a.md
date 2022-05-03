---
title: " GraphAdaMix: Enhancing Node Representations with Graph Adaptive Mixtures "
abstract: " Graph Neural Networks (GNNs) are the current state-of-the-art models in
  learning node representations for many predictive tasks on graphs. Typically, GNNs
  reuses the same set of model parameters across all nodes in the graph to improve
  the training efficiency and exploit the translationally-invariant properties in
  many datasets. However, the parameter sharing scheme prevents GNNs from distinguishing
  two nodes having the same local structure and that the translation invariance property
  may not exhibit in real-world graphs. In this paper, we present Graph Adaptive Mixtures
  (GraphAdaMix), a novel approach for learning node representations in a graph by
  introducing multiple independent GNN models and a trainable mixture distribution
  for each node. GraphAdaMix can adapt to tasks with different settings. Specifically,
  for semi-supervised tasks, we optimize GraphAdaMix using the Expectation-Maximization
  (EM) algorithm, while in unsupervised settings, GraphAdaMix is trained following
  the paradigm of contrastive learning. We evaluate GraphAdaMix on ten benchmark datasets
  with extensive experiments. GraphAdaMix is demonstrated to consistently boost state-of-the-art
  GNN variants in semi-supervised and unsupervised node classification tasks. The
  code of GraphAdaMix is available online. "
software: " https://github.com/handasontam/GraphAdaMix "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sun-handason-tam22a
month: 0
tex_title: " GraphAdaMix: Enhancing Node Representations with Graph Adaptive Mixtures "
firstpage: 9890
lastpage: 9907
page: 9890-9907
order: 9890
cycles: false
bibtex_author: Sun Handason Tam, Da and Xie, Siyue and Cheong Lau, Wing
author:
- given: Da
  family: Sun Handason Tam
- given: Siyue
  family: Xie
- given: Wing
  family: Cheong Lau
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
pdf: https://proceedings.mlr.press/v151/sun-handason-tam22a/sun-handason-tam22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
