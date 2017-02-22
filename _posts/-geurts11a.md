---
title: Learning from positive and unlabeled examples by enforcing statistical significance
abstract: Given a finite but large set of objects described by a vector of features,
  only a small subset of which have been labeled as ``"positive"'' with respect to
  a class of interest, we consider the problem of characterizing the positive class.
  We formalize this as the problem of learning a feature based score function that
  minimizes the p-value of a non parametric statistical hypothesis test. For linear
  score functions over the original feature space or over one of its kernelized versions,
  we provide a solution of this problem computed by a one-class SVM applied on a surrogate
  dataset obtained by sampling subsets of the overall set of objects and representing
  them by their average feature-vector shifted by the average feature-vector of the
  original sample of positive examples. We carry out experiments with this method
  on the prediction of targets of transcription factors in two different organisms,
  E. Coli and S. Cererevisiae. Our method extends enrichment analysis commonly carried
  out in Bioinformatics and its results outperform common solutions to this problem.
  [pdf][supplementary]
pdf: "./geurts11a/geurts11a.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/geurts11a/geurts11aSupple.pdf
layout: inproceedings
key: geurts11a
month: 0
firstpage: 305
lastpage: 314
origpdf: http://jmlr.org/proceedings/papers/v15/geurts11a/geurts11a.pdf
sections: 
authors:
- given: Pierre
  family: Geurts
---