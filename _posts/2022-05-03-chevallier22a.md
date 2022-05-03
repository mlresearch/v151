---
title: " Efficient computation of the the volume of a polytope in high-dimensions
  using Piecewise Deterministic Markov Processes "
abstract: " Computing the volume of a polytope in high dimensions is computationally
  challenging but has wide applications. Current state-of-the-art algorithms to compute
  such volumes rely on efficient sampling of a Gaussian distribution restricted to
  the polytope, using e.g. Hamiltonian Monte Carlo. We present a new sampling strategy
  that uses a Piecewise Deterministic Markov Process. Like Hamiltonian Monte Carlo,
  this new method involves simulating trajectories of a non-reversible process and
  inherits similar good mixing properties. However, importantly, the process can be
  simulated more easily due to its piecewise linear trajectories – and this leads
  to a reduction of the computational cost by a factor of the dimension of the space.
  Our experiments indicate that our method is numerically robust and is one order
  of magnitude faster (or better) than existing methods using Hamiltonian Monte Carlo.
  On a single core processor, we report computational time of a few minutes up to
  dimension 500. "
software: " https://github.com/augustin-chevallier/PolytopeVolume "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chevallier22a
month: 0
tex_title: " Efficient computation of the the volume of a polytope in high-dimensions
  using Piecewise Deterministic Markov Processes "
firstpage: 10146
lastpage: 10160
page: 10146-10160
order: 10146
cycles: false
bibtex_author: Chevallier, Augustin and Cazals, Fr\'ed\'eric and Fearnhead, Paul
author:
- given: Augustin
  family: Chevallier
- given: Frédéric
  family: Cazals
- given: Paul
  family: Fearnhead
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
pdf: https://proceedings.mlr.press/v151/chevallier22a/chevallier22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
