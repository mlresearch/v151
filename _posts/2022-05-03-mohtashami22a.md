---
title: " Masked Training of Neural Networks with Partial Gradients "
abstract: " State-of-the-art training algorithms for deep learning models are based
  on stochastic gradient descent (SGD). Recently, many variations have been explored:
  perturbing parameters for better accuracy (such as in Extragradient), limiting SGD
  updates to a subset of parameters for increased efficiency (such as meProp) or a
  combination of both (such as Dropout). However, the convergence of these methods
  is often not studied in theory. We propose a unified theoretical framework to study
  such SGD variants—encompassing the aforementioned algorithms and additionally a
  broad variety of methods used for communication efficient training or model compression.
  Our insights can be used as a guide to improve the efficiency of such methods and
  facilitate generalization to new applications. As an example, we tackle the task
  of jointly training networks, a version of which (limited to sub-networks) is used
  to create Slimmable Networks. By training a low-rank Transformer jointly with a
  standard one we obtain superior performance than when it is trained separately. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mohtashami22a
month: 0
tex_title: " Masked Training of Neural Networks with Partial Gradients "
firstpage: 5876
lastpage: 5890
page: 5876-5890
order: 5876
cycles: false
bibtex_author: Mohtashami, Amirkeivan and Jaggi, Martin and Stich, Sebastian
author:
- given: Amirkeivan
  family: Mohtashami
- given: Martin
  family: Jaggi
- given: Sebastian
  family: Stich
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
pdf: https://proceedings.mlr.press/v151/mohtashami22a/mohtashami22a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v151/mohtashami22a/mohtashami22a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
