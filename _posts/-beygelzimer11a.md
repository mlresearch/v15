---
section: notable
title: Contextual Bandit Algorithms with Supervised Learning Guarantees
abstract: 'We address the problem of competing with any large set of $N$ policies
  in the non-stochastic bandit setting, where the learner must repeatedly select among
  $K$ actions but observes only the reward of the chosen action.  We present a modification
  of the Exp4 algorithm of [Auer et al. 2002] called Exp4.P, which with high probability
  incurs regret at most $O(\sqrt{KT\ln N})$.  Such a bound does not hold for Exp4
  due to the large variance of the importance-weighted estimates used in the algorithm.
  The new algorithm is tested empirically in a large-scale, real-world dataset.  For
  the stochastic version of the problem, we can use Exp4.P as a subroutine to compete
  with a possibly infinite set of policies of VC-dimension $d$ while incurring regret
  at most $O(\sqrt{Td\ln T})$ with high probability.  These guarantees improve on
  those of all previous algorithms, whether in a stochastic or adversarial environment,
  and bring us closer to providing guarantees for this setting that are comparable
  to those in standard supervised learning.  '
pdf: "./beygelzimer11a/beygelzimer11a.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/beygelzimer11a/beygelzimer11aSupple.pdf
discussion: mcmahan11a.html
layout: inproceedings
key: beygelzimer11a
month: 0
firstpage: 19
lastpage: 26
origpdf: http://jmlr.org/proceedings/papers/v15/beygelzimer11a/beygelzimer11a.pdf
sections: 
authors:
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
---
