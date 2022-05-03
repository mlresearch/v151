---
title: " Learning Proposals for Practical Energy-Based Regression "
abstract: " Energy-based models (EBMs) have experienced a resurgence within machine
  learning in recent years, including as a promising alternative for probabilistic
  regression. However, energy-based regression requires a proposal distribution to
  be manually designed for training, and an initial estimate has to be provided at
  test-time. We address both of these issues by introducing a conceptually simple
  method to automatically learn an effective proposal distribution, which is parameterized
  by a separate network head. To this end, we derive a surprising result, leading
  to a unified training objective that jointly minimizes the KL divergence from the
  proposal to the EBM, and the negative log-likelihood of the EBM. At test-time, we
  can then employ importance sampling with the trained proposal to efficiently evaluate
  the learned EBM and produce stand-alone predictions. Furthermore, we utilize our
  derived training objective to learn mixture density networks (MDNs) with a jointly
  trained energy-based teacher, consistently outperforming conventional MDN training
  on four real-world regression tasks within computer vision. Code is available at
  https://github.com/fregu856/ebms_proposals. "
software: " https://github.com/fregu856/ebms_proposals "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gustafsson22a
month: 0
tex_title: " Learning Proposals for Practical Energy-Based Regression "
firstpage: 4685
lastpage: 4704
page: 4685-4704
order: 4685
cycles: false
bibtex_author: Gustafsson, Fredrik K. and Danelljan, Martin and Sch\"on, Thomas B.
author:
- given: Fredrik K.
  family: Gustafsson
- given: Martin
  family: Danelljan
- given: Thomas B.
  family: Schön
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
pdf: https://proceedings.mlr.press/v151/gustafsson22a/gustafsson22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
