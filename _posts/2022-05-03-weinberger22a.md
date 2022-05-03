---
title: " Moment Matching Deep Contrastive Latent Variable Models "
abstract: " In the contrastive analysis (CA) setting, machine learning practitioners
  are specifically interested in discovering patterns that are enriched in a target
  dataset as compared to a background dataset generated from sources of variation
  irrelevant to the task at hand. For example, a biomedical data analyst may seek
  to understand variations in genomic data only present among patients with a given
  disease as opposed to those also present in healthy control subjects. Such scenarios
  have motivated the development of contrastive latent variable models to isolate
  variations unique to these target datasets from those shared across the target and
  background datasets, with current state of the art models based on the variational
  autoencoder (VAE) framework. However, previously proposed models do not explicitly
  enforce the constraints on latent variables underlying CA, potentially leading to
  the undesirable leakage of information between the two sets of latent variables.
  Here we propose the moment matching contrastive VAE (MM-cVAE), a reformulation of
  the VAE for CA that uses the maximum mean discrepancy to explicitly enforce two
  crucial latent variable constraints underlying CA. On three challenging CA tasks
  we find that our method outperforms the previous state-of-the-art both qualitatively
  and on a set of quantitative metrics. "
software: " https://github.com/suinleelab/MM-cVAE "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: weinberger22a
month: 0
tex_title: " Moment Matching Deep Contrastive Latent Variable Models "
firstpage: 2354
lastpage: 2371
page: 2354-2371
order: 2354
cycles: false
bibtex_author: Weinberger, Ethan and Beebe-Wang, Nicasia and Lee, Su-In
author:
- given: Ethan
  family: Weinberger
- given: Nicasia
  family: Beebe-Wang
- given: Su-In
  family: Lee
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
pdf: https://proceedings.mlr.press/v151/weinberger22a/weinberger22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
