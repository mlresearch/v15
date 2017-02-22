---
title: Bagged Structure Learning of Bayesian Network
abstract: We present a novel approach for density estimation using Bayesian networks
  when faced with scarce and partially observed data.  Our approach relies on Efron's
  bootstrap framework, and replaces the standard model selection score by a bootstrap
  aggregation objective aimed at sifting out bad decisions during the learning procedure.
  Unlike previous bootstrap or MCMC based approaches that are only aimed at recovering
  specific structural features, we learn a concrete density model that can be used
  for probabilistic generalization. To make use of our objective when some of the
  data is missing, we propose a bagged structural EM procedure that does not incur
  the heavy computational cost typically associated with a bootstrap-based approach.
  We compare our bagged objective to the Bayesian score and the Bayesian information
  criterion (BIC), as well as other bootstrap-based model selection objectives, and
  demonstrate its effectiveness in improving generalization performance for varied
  real-life datasets. [pdf]
pdf: "./elidan11a/elidan11a.pdf"
layout: inproceedings
key: elidan11a
month: 0
firstpage: 251
lastpage: 259
origpdf: http://jmlr.org/proceedings/papers/v15/elidan11a/elidan11a.pdf
sections: 
authors:
- given: Gal
  family: Elidan
---
