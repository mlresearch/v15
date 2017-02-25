---
title: Active Boosted Learning (ActBoost)
abstract: Active learning deals with the problem of selecting a small subset of examples
  to label, from a pool of unlabeled data, for training a good classifier. We develop
  an active learning algorithm algorithm in the boosting framework. In contrast to
  much of the recent efforts, which has focused on selecting the most ambiguous unlabeled
  example to label based on the current learned classifier, our algorithm selects
  examples to maximally reduce the volume of the version space of feasible boosted
  classifiers. We show that under suitable sparsity assumptions, this strategy achieves
  the generalization error performance of a boosted classifier trained on the entire
  data set while only selecting logarithmically many unlabeled samples to label. We
  also establish a partial negative result, in that with out imposing structural assumptions
  it is difficult to guarantee generalization error performance. We explicitly characterize
  our convergence rate in terms of the sign pattern differences produced by the weak
  learners on the unlabeled data. We also present a convex relaxation to account for
  the non-convex sparse structure and show that the computational complexity of the
  resulting algorithm scales polynomially in the number of weak learners. We test
  ActBoost on several datasets to illustrate its performance and demonstrate its robustness
  to initialization. [pdf][supplementary]
pdf: http://proceedings.mlr.press/v15/trapeznikov11a/trapeznikov11a.pdf
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/trapeznikov11a/trapeznikov11aSupple.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: trapeznikov11a
month: 0
tex_title: Active Boosted Learning (ActBoost)
firstpage: 743
lastpage: 751
page: 743-751
sections: 
author:
- given: Kirill
  family: Trapeznikov
- given: Venkatesh
  family: Saligrama
- given: David
  family: Castanon
date: 2011-06-14
address: Fort Lauderdale, FL, USA
publisher: PMLR
container-title: Proceedings of the Fourteenth International Conference on Artificial
  Intelligence and Statistics
volume: '15'
genre: inproceedings
issued:
  date-parts:
  - 2011
  - 6
  - 14
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
