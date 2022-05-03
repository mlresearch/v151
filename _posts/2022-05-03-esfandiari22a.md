---
title: " Label differential privacy via clustering "
abstract: " We present new mechanisms for label differential privacy, a relaxation
  of differentially private machine learning that only protects the privacy of the
  labels in the training set. Our mechanisms cluster the examples in the training
  set using their (non-private) feature vectors, randomly re-sample each label from
  examples in the same cluster, and output a training set with noisy labels as well
  as a modified version of the true loss function. We prove that when the clusters
  are both large and high-quality, the model that minimizes the modified loss on the
  noisy training set converges to small excess risk at a rate that is comparable to
  the rate for non-private learning. We also describe a learning problem in which
  large clusters are necessary to achieve both strong privacy and either good precision
  or good recall. Our experiments show that randomizing the labels within each cluster
  significantly improves the privacy vs. accuracy trade-off compared to applying uniform
  randomized response to the labels, and also compared to learning a model via DP-SGD. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: esfandiari22a
month: 0
tex_title: " Label differential privacy via clustering "
firstpage: 7055
lastpage: 7075
page: 7055-7075
order: 7055
cycles: false
bibtex_author: Esfandiari, Hossein and Mirrokni, Vahab and Syed, Umar and Vassilvitskii,
  Sergei
author:
- given: Hossein
  family: Esfandiari
- given: Vahab
  family: Mirrokni
- given: Umar
  family: Syed
- given: Sergei
  family: Vassilvitskii
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
pdf: https://proceedings.mlr.press/v151/esfandiari22a/esfandiari22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
