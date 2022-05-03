---
title: " Adaptive Multi-Goal Exploration "
abstract: ' We introduce a generic strategy for provably efficient multi-goal exploration.
  It relies on AdaGoal, a novel goal selection scheme that leverages a measure of
  uncertainty in reaching states to adaptively target goals that are neither too difficult
  nor too easy. We show how AdaGoal can be used to tackle the objective of learning
  an $\epsilon$-optimal goal-conditioned policy for the (initially unknown) set of
  goal states that are reachable within $L$ steps in expectation from a reference
  state $s_0$ in a reward-free Markov decision process. In the tabular case with $S$
  states and $A$ actions, our algorithm requires $\tilde{O}(L^3 S A \epsilon^{-2})$
  exploration steps, which is nearly minimax optimal. We also readily instantiate
  AdaGoal in linear mixture Markov decision processes, yielding the first goal-oriented
  PAC guarantee with linear function approximation. Beyond its strong theoretical
  guarantees, we anchor AdaGoal in goal-conditioned deep reinforcement learning, both
  conceptually and empirically, by connecting its idea of selecting "uncertain" goals
  to maximizing value ensemble disagreement. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tarbouriech22a
month: 0
tex_title: " Adaptive Multi-Goal Exploration "
firstpage: 7349
lastpage: 7383
page: 7349-7383
order: 7349
cycles: false
bibtex_author: Tarbouriech, Jean and Darwiche Domingues, Omar and Menard, Pierre and
  Pirotta, Matteo and Valko, Michal and Lazaric, Alessandro
author:
- given: Jean
  family: Tarbouriech
- given: Omar
  family: Darwiche Domingues
- given: Pierre
  family: Menard
- given: Matteo
  family: Pirotta
- given: Michal
  family: Valko
- given: Alessandro
  family: Lazaric
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
pdf: https://proceedings.mlr.press/v151/tarbouriech22a/tarbouriech22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
