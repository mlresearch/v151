---
title: " Learning Sparse Fixed-Structure Gaussian Bayesian Networks "
abstract: " Gaussian Bayesian networks are widely used to model causal interactions
  among continuous variables. In this work, we study the problem of learning a fixed-structure
  Gaussian Bayesian network up to a bounded error in total variation distance. We
  analyze the commonly used node-wise least squares regression LeastSquares and prove
  that it has the near-optimal sample complexity. We also study a couple of new algorithms
  for the problem: BatchAvgLeastSquares takes the average of several batches of least
  squares solutions at each node, so that one can interpolate between the batch size
  and the number of batches. We show that BatchAvgLeastSquares also has near-optimal
  sample complexity. CauchyEst takes the median of solutions to several batches of
  linear systems at each node. We show that the algorithm specialized to polytrees,
  CauchyEstTree, has near-optimal sample complexity. Experimentally, we show that
  for uncontaminated, realizable data, the LeastSquares algorithm performs best, but
  in the presence of contamination or DAG misspecification, CauchyEst/CauchyEstTree
  and BatchAvgLeastSquares respectively perform better. "
software: " https://github.com/YohannaWANG/CauchyEst "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya22b
month: 0
tex_title: " Learning Sparse Fixed-Structure Gaussian Bayesian Networks "
firstpage: 9400
lastpage: 9429
page: 9400-9429
order: 9400
cycles: false
bibtex_author: Bhattacharyya, Arnab and Choo, Davin and Gajjala, Rishikesh and Gayen,
  Sutanu and Wang, Yuhao
author:
- given: Arnab
  family: Bhattacharyya
- given: Davin
  family: Choo
- given: Rishikesh
  family: Gajjala
- given: Sutanu
  family: Gayen
- given: Yuhao
  family: Wang
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
pdf: https://proceedings.mlr.press/v151/bhattacharyya22b/bhattacharyya22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
