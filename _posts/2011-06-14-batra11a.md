---
title: 'Tighter Relaxations for MAP-MRF Inference: A Local Primal-Dual Gap based Separation
  Algorithm'
abstract: We propose an efficient and adaptive method for MAP-MRF inference that provides
  increasingly tighter upper and lower bounds on the optimal objective. Similar to
  Sontag et al. (2008), our method starts by solving the first-order LOCAL(G) linear
  programming relaxation. This is followed by an adaptive tightening of the relaxation
  where we incrementally add higher-order interactions to enforce proper marginalization
  over groups of variables. Computing the best interaction to add is an NP-hard problem.
  We show good solutions to this problem can be readily obtained from ``local primal-dual
  gaps'' given the current primal solution and a dual reparameterization vector. This
  is not only extremely efficient, but in contrast to previous approaches, also allows
  us to search over prohibitively large sets of candidate interactions to add. We
  demonstrate the superiority of our approach on MAP-MRF inference problems encountered
  in computer vision. [pdf]
pdf: "./batra11a/batra11a.pdf"
layout: inproceedings
key: batra11a
month: 0
firstpage: 146
lastpage: 154
origpdf: http://jmlr.org/proceedings/papers/v15/batra11a/batra11a.pdf
sections: 
authors:
- given: Dhruv
  family: Batra
- given: Sebastian
  family: Nowozin
- given: Pushmeet
  family: Kohli
---
