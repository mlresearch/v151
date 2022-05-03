---
title: " Lifted Primal-Dual Method for Bilinearly Coupled Smooth Minimax Optimization "
abstract: " We study the bilinearly coupled minimax problem: $\\min_{x} \\max_{y}
  f(x) + y^\\top A x - h(y)$, where $f$ and $h$ are both strongly convex smooth functions
  and admit first-order gradient oracles. Surprisingly, no known first-order algorithms
  have hitherto achieved the lower complexity bound of $\\Omega((\\sqrt{\\frac{L_x}{\\mu_x}}
  + \\frac{\\|A\\|}{\\sqrt{\\mu_x \\mu_y}} + \\sqrt{\\frac{L_y}{\\mu_y}}) \\log(\\frac1{\\varepsilon}))$
  for solving this problem up to an $\\varepsilon$ primal-dual gap in the general
  parameter regime, where $L_x, L_y,\\mu_x,\\mu_y$ are the corresponding smoothness
  and strongly convexity constants. We close this gap by devising the first optimal
  algorithm, the Lifted Primal-Dual (LPD) method. Our method lifts the objective into
  an extended form that allows both the smooth terms and the bilinear term to be handled
  optimally and seamlessly with the same primal-dual framework. Besides optimality,
  our method yields a desirably simple single-loop algorithm that uses only one gradient
  oracle call per iteration. Moreover, when $f$ is just convex, the same algorithm
  applied to a smoothed objective achieves the nearly optimal iteration complexity.
  We also provide a direct single-loop algorithm, using the LPD method, that achieves
  the iteration complexity of $O(\\sqrt{\\frac{L_x}{\\varepsilon}} + \\frac{\\|A\\|}{\\sqrt{\\mu_y
  \\varepsilon}} + \\sqrt{\\frac{L_y}{\\varepsilon}})$. Numerical experiments on quadratic
  minimax problems and policy evaluation problems further demonstrate the fast convergence
  of our algorithm in practice. "
software: " https://github.com/tkkiran/LiftedPrimalDual "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thekumparampil22a
month: 0
tex_title: " Lifted Primal-Dual Method for Bilinearly Coupled Smooth Minimax Optimization "
firstpage: 4281
lastpage: 4308
page: 4281-4308
order: 4281
cycles: false
bibtex_author: Thekumparampil, Kiran K. and He, Niao and Oh, Sewoong
author:
- given: Kiran K.
  family: Thekumparampil
- given: Niao
  family: He
- given: Sewoong
  family: Oh
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
pdf: https://proceedings.mlr.press/v151/thekumparampil22a/thekumparampil22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
