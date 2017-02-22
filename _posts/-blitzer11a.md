---
title: Domain Adaptation with Coupled Subspaces
abstract: 'Domain adaptation algorithms address a key issue in applied machine learning:
  How can we train a system under a source distribution but achieve high performance
  under a different target distribution? We tackle this question for divergent distributions
  where crucial predictive target features may not even have support under the source
  distribution. In this setting, the key intuition is that that if we can link target-specific
  features to source features, we can learn effectively using only source labeled
  data. We formalize this intuition, as well as the assumptions under which such coupled
  learning is possible. This allows us to give finite sample target error bounds (using
  only source training data) and an algorithm which performs at the state-of-the-art
  on two natural language processing adaptation tasks which are characterized by novel
  target features. [pdf][supplementary]'
pdf: "./blitzer11a/blitzer11a.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v15/blitzer11a/blitzer11aSupple.pdf
layout: inproceedings
key: blitzer11a
month: 0
firstpage: 173
lastpage: 181
origpdf: http://jmlr.org/proceedings/papers/v15/blitzer11a/blitzer11a.pdf
sections: 
authors:
- given: John
  family: Blitzer
- given: Sham
  family: Kakade
- given: Dean
  family: Foster
---