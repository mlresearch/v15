---
section: notable
title: Contextual Bandit Algorithms with Supervised Learning Guarantees
abstract: 'We address the problem of competing with any large set of N policies in
  the non-stochastic bandit setting, where the learner must repeatedly select among
  K actions but observes only the reward of the chosen action.  We present a modification
  of the Exp4 algorithm of [Auer et al. 2002] called Exp4.P, which with high probability
  incurs regret at most O(\sqrtKT\ln N).  Such a bound does not hold for Exp4 due
  to the large variance of the importance-weighted estimates used in the algorithm.
  The new algorithm is tested empirically in a large-scale, real-world dataset.  For
  the stochastic version of the problem, we can use Exp4.P as a subroutine to compete
  with a possibly infinite set of policies of VC-dimension d while incurring regret
  at most O(\sqrtTd\ln T) with high probability.  These guarantees improve on those
  of all previous algorithms, whether in a stochastic or adversarial environment,
  and bring us closer to providing guarantees for this setting that are comparable
  to those in standard supervised learning.  '
pdf: http://proceedings.mlr.press/v15/beygelzimer11a/beygelzimer11a.pdf
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/beygelzimer11a/beygelzimer11aSupple.pdf
discussion: mcmahan11a.html
layout: inproceedings
id: beygelzimer11a
month: 0
firstpage: 19
lastpage: 26
page: 19-26
sections: 
author:
- given: Alina
  family: Beygelzimer
- given: John
  family: Langford
- given: Lihong
  family: Li
- given: Lev
  family: Reyzin
- given: Robert
  family: Schapire
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
