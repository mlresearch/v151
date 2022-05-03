---
title: " The Importance of Future Information in Credit Card Fraud Detection "
abstract: ' Fraud detection systems (FDS) mainly perform two tasks: (i) real-time
  detection while the payment is being processed and (ii) posterior detection to block
  the card retrospectively and avoid further frauds. Since human verification is often
  necessary and the payment processing time is limited, the second task manages the
  largest volume of transactions. In the literature, fraud detection challenges and
  algorithms performance are widely studied but the very formulation of the problem
  is never disrupted: it aims at predicting if a transaction is fraudulent based on
  its characteristics and the past transactions of the cardholder. Yet, in posterior
  detection, verification often takes days, so new payments on the card become available
  before a decision is taken. This is our motivation to propose a new paradigm: posterior
  fraud detection with "future" information. We start by providing evidence of the
  on-time availability of subsequent transactions, usable as extra context to improve
  detection. We then design a Bidirectional LSTM to make use of these transactions.
  On a real-world dataset with over 30 million transactions, it achieves higher performance
  than a regular LSTM, which is the state-of-the-art classifier for fraud detection
  that only uses the past context. We also introduce new metrics to show that the
  proposal catches more frauds, more compromised cards, and based on their earliest
  frauds. We believe that future works on this new paradigm will have a significant
  impact on the detection of compromised cards. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bach-nguyen22a
month: 0
tex_title: " The Importance of Future Information in Credit Card Fraud Detection "
firstpage: 10067
lastpage: 10077
page: 10067-10077
order: 10067
cycles: false
bibtex_author: Bach Nguyen, Van and Ghosh Dastidar, Kanishka and Granitzer, Michael
  and Siblini, Wissam
author:
- given: Van
  family: Bach Nguyen
- given: Kanishka
  family: Ghosh Dastidar
- given: Michael
  family: Granitzer
- given: Wissam
  family: Siblini
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
pdf: https://proceedings.mlr.press/v151/bach-nguyen22a/bach-nguyen22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
