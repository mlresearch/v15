---
title: A Reduction of Imitation Learning and Structured Prediction to No-Regret Online
  Learning
abstract: Sequential prediction problems such as imitation learning, where future
  observations depend on previous predictions (actions), violate the common i.i.d.
  assumptions made in statistical learning. This leads to poor performance in theory
  and often in practice. Some recent approaches provide stronger guarantees in this
  setting, but remain somewhat unsatisfactory as they train either non-stationary
  or stochastic policies and require a large number of iterations. In this paper,
  we propose a new iterative algorithm, which trains a stationary deterministic policy,
  that can be seen as a no regret algorithm in an online learning setting. We show
  that any such no regret algorithm, combined with additional reduction assumptions,
  must find a policy with good performance under the distribution of observations
  it induces in such sequential settings. We demonstrate that this new approach outperforms
  previous approaches on two challenging imitation learning problems and a benchmark
  sequence labeling problem. [pdf]
pdf: "./ross11a/ross11a.pdf"
layout: inproceedings
key: ross11a
month: 0
firstpage: 627
lastpage: 635
origpdf: http://jmlr.org/proceedings/papers/v15/ross11a/ross11a.pdf
sections: 
authors:
- given: Stephane
  family: Ross
- given: Geoffrey
  family: Gordon
- given: Drew
  family: Bagnell
---