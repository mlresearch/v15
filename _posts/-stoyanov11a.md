---
title: Empirical Risk Minimization of Graphical Model Parameters Given Approximate
  Inference, Decoding, and Model Structure
abstract: Graphical models are often used ``inappropriately,'' with approximations
  in the topology, inference, and prediction. Yet it is still common to train their  parameters
  to approximately maximize training likelihood.  We argue that instead, one should
  seek the parameters that minimize the empirical risk of the entire imperfect system.  We
  show how to locally optimize this risk using back-propagation and stochastic meta-descent.
  Over a range of synthetic-data problems, compared to the usual practice of choosing
  approximate MAP parameters, our approach significantly reduces loss on test data,
  sometimes by an order of magnitude. [pdf][supplementary]
pdf: "./stoyanov11a/stoyanov11a.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/stoyanov11a/stoyanov11aSupple.pdf
layout: inproceedings
key: stoyanov11a
month: 0
firstpage: 725
lastpage: 733
origpdf: http://jmlr.org/proceedings/papers/v15/stoyanov11a/stoyanov11a.pdf
sections: 
authors:
- given: Veselin
  family: Stoyanov
- given: Alexander
  family: Ropson
- given: Jason
  family: Eisner
---