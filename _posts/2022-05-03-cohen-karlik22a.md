---
title: " On the Implicit Bias of Gradient Descent for Temporal Extrapolation "
abstract: " When using recurrent neural networks (RNNs) it is common practice to apply
  trained models to sequences longer than those seen in training. This “extrapolating”
  usage deviates from the traditional statistical learning setup where guarantees
  are provided under the assumption that train and test distributions are identical.
  Here we set out to understand when RNNs can extrapolate, focusing on a simple case
  where the data generating distribution is memoryless. We first show that even with
  infinite training data, there exist RNN models that interpolate perfectly (i.e.,
  they fit the training data) yet extrapolate poorly to longer sequences. We then
  show that if gradient descent is used for training, learning will converge to perfect
  extrapolation under certain assumptions on initialization. Our results complement
  recent studies on the implicit bias of gradient descent, showing that it plays a
  key role in extrapolation when learning temporal prediction models. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-karlik22a
month: 0
tex_title: " On the Implicit Bias of Gradient Descent for Temporal Extrapolation "
firstpage: 10966
lastpage: 10981
page: 10966-10981
order: 10966
cycles: false
bibtex_author: Cohen-Karlik, Edo and Ben David, Avichai and Cohen, Nadav and Globerson,
  Amir
author:
- given: Edo
  family: Cohen-Karlik
- given: Avichai
  family: Ben David
- given: Nadav
  family: Cohen
- given: Amir
  family: Globerson
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
pdf: https://proceedings.mlr.press/v151/cohen-karlik22a/cohen-karlik22a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v151/cohen-karlik22a/cohen-karlik22a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
