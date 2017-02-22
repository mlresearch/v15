---
title: 'Active Clustering: Robust and Efficient Hierarchical Clustering using Adaptively
  Selected Similarities'
abstract: Hierarchical clustering based on pairwise similarities is a common tool
  used in a broad range of scientific applications. However, in many problems it may
  be expensive to obtain or compute similarities between the items to be clustered.
  This paper investigates the possibility of hierarchical clustering of N items based
  on a small subset of pairwise similarities, significantly less than the complete
  set of N(N-1)/2 similarities.  First, we show that, if the intracluster similarities
  exceed intercluster similarities, then it is possible to correctly determine the
  hierarchical clustering from as few as 3N log N similarities.  We demonstrate this
  order of magnitude saving in the number of pairwise similarities necessitates sequentially
  selecting which similarities to obtain in an adaptive fashion, rather than picking
  them at random. Finally, we propose an active clustering method that is robust to
  a limited fraction of anomalous similarities, and show how even in the presence
  of these noisy similarity values we can resolve the hierarchical clustering using
  only O(N log^2 N) pairwise similarities. [pdf]
pdf: "./eriksson11a/eriksson11a.pdf"
layout: inproceedings
key: eriksson11a
month: 0
firstpage: 260
lastpage: 268
origpdf: http://jmlr.org/proceedings/papers/v15/eriksson11a/eriksson11a.pdf
sections: 
authors:
- given: Brian
  family: Eriksson
- given: Gautam
  family: Dasarathy
- given: Aarti
  family: Singh
- given: Rob
  family: Nowak
---