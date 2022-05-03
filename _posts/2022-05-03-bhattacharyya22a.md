---
title: " Efficient interventional distribution learning in the PAC framework "
abstract: " We consider the problem of efficiently inferring interventional distributions
  in a causal Bayesian network from a finite number of observations. Let P be a causal
  model on a set V of observable variables on a given causal graph G. For sets $X,Y
  \\subseteq V$, and setting x to $X$, $P_x(Y)$ denotes the interventional distribution
  on Y with respect to an intervention x to variables X. Shpitser and Pearl (AAAI
  2006), building on the work of Tian and Pearl (AAAI 2001), proved that the ID algorithm
  is sound and complete for recovering P_x(Y) from observations. We give the first
  provably efficient version of the ID algorithm. In particular, under natural assumptions,
  we give a polynomial-time algorithm that on input a causal graph G on observable
  variables V, a setting x of a set $X \\subseteq V$ of bounded size, outputs succinct
  descriptions of both an evaluator and a generator for a distribution $\\hat{P}$
  that is epsilon-close (in total variation distance) to $P_x(Y)$ where $Y = V  X$,
  if $P_x(Y)$ is identifiable. We also show that when Y is an arbitrary subset of
  $V  X$, there is no efficient algorithm that outputs an evaluator of a distribution
  that is epsilon-close to $P_x(Y)$ unless all problems that have statistical zero-knowledge
  proofs, including the Graph Isomorphism problem, have efficient randomized algorithms. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya22a
month: 0
tex_title: " Efficient interventional distribution learning in the PAC framework "
firstpage: 7531
lastpage: 7549
page: 7531-7549
order: 7531
cycles: false
bibtex_author: Bhattacharyya, Arnab and Gayen, Sutanu and Kandasamy, Saravanan and
  Raval, Vedant and Variyam, Vinodchandran N.
author:
- given: Arnab
  family: Bhattacharyya
- given: Sutanu
  family: Gayen
- given: Saravanan
  family: Kandasamy
- given: Vedant
  family: Raval
- given: Vinodchandran N.
  family: Variyam
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
pdf: https://proceedings.mlr.press/v151/bhattacharyya22a/bhattacharyya22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
