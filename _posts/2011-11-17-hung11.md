---
title: Multi-label Active Learning with Auxiliary Learner
abstract: Multi-label active learning is an important problem because of the expensive
  labeling cost in multi-label classification applications. A state-of-the-art approach
  for multi-label active learning, maximum loss reduction with maximum confidence
  (MMC), heavily depends on the binary relevance support vector machine in both learning
  and querying. Nevertheless, it is not clear whether the heavy dependence is necessary
  or unrivaled. In this work, we extend MMC to a more general framework that removes
  the heavy dependence and clarifies the roles of each component in MMC. In particular,
  the framework is characterized by a major learner for making predictions, an auxiliary
  learner for helping with query decisions and a query criterion based on the disagreement
  between the two learners. The framework takes MMC and several baseline multi-label
  active learning algorithms as special cases. With the flexibility of the general
  framework, we design two criteria other than the one used by MMC. We also explore
  the possibility of using learners other than the binary relevance support vector
  machine for multi-label active learning. Experimental results demonstrate that a
  new criterion, soft Hamming loss reduction, is usually better than the original
  MMC criterion across different pairs of major/auxiliary learners, and validate the
  usefulness of the proposed framework.
pdf: "./hung11/hung11.pdf"
layout: inproceedings
key: hung11
month: 0
firstpage: 315
lastpage: 332
origpdf: http://jmlr.org/proceedings/papers/v20/hung11/hung11.pdf
sections: 
authors:
- given: C.-W.
  family: Hung
- given: H.-T.
  family: Lin
---
