---
section: notable
title: The Neural Autoregressive Distribution Estimator
abstract: 'We describe a new approach for modeling the distribution of high-dimensional
  vectors of discrete variables. This model is inspired by the restricted Boltzmann
  machine (RBM), which has been shown to be a powerful model of such distributions.
  However, an RBM typically does not provide a tractable distribution estimator, since
  evaluating the probability it assigns to some given observation requires the computation
  of the so-called partition function, which itself is intractable for RBMs of even
  moderate size. Our model circumvents this difficulty by decomposing the joint distribution
  of observations into tractable conditional distributions and modeling each conditional
  using a non-linear function similar to a conditional of an RBM. Our model can also
  be interpreted as an autoencoder wired such that its output can be used to assign
  valid probabilities to observations. We show that this new model outperforms other
  multivariate binary distribution estimators on several datasets and performs similarly
  to a large (but intractable) RBM.  '
pdf: "./larochelle11a/larochelle11a.pdf"
discussion: bengio11a.html
layout: inproceedings
id: larochelle11a
month: 0
firstpage: 29
lastpage: 37
page: 29-37
origpdf: http://jmlr.org/proceedings/papers/v15/larochelle11a/larochelle11a.pdf
sections: 
author:
- given: Hugo
  family: Larochelle
- given: Iain
  family: Murray
date: '2011-06-14 00:00:29'
publisher: PMLR
---
