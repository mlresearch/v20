---
title: Bayesian inference for statistical abduction using Markov chain Monte Carlo
abstract: Abduction is one of the basic logical inferences (deduction, induction and
  abduction) and derives the best explanations for our observation. Statistical abduction
  attempts to define a probability distribution over explanations and to evaluate
  them by their probabilities. The framework of statistical abduction is general since
  many well-known probabilistic models, i.e., BNs, HMMs and PCFGs, are formulated
  as statistical abduction. Logic-based probabilistic models (LBPMs) have been developed
  as a way to combine probabilities and logic, and it enables us to perform statistical
  abduction. However, most of existing LBPMs impose restrictions on explanations (logical
  formulas) to realize efficient probability computation and learning. To relax those
  restrictions, we propose two MCMC (Markov chain Monte Carlo) methods for Bayesian
  inference on LBPMs using binary decision diagrams. The main advantage of our methods
  over existing methods is that it has no restriction on formulas. In the context
  of statistical abduction with Bayesian inference, whereas our deterministic knowledge
  can be described by logical formulas as rules and facts, our non-deterministic knowledge
  like frequency and preference can be reflected in a prior distribution in Bayesian
  inference. To illustrate our methods, we first formulate LDA (latent Dirichlet allocation)
  which is a well-known generative probabilistic model for bag-of-words as a form
  of statistical abduction, and compare the learning result of our methods with that
  of an MCMC method called collapsed Gibbs sampling specialized for LDA. We also apply
  our methods to diagnosis for failure in a logic circuit and evaluate explanations
  using a posterior distribution approximated by our method. The experiment shows
  Bayesian inference achieves better predicting accuracy than that of Maximum likelihood
  estimation.
pdf: "./ishihata11/ishihata11.pdf"
layout: inproceedings
key: ishihata11
month: 0
firstpage: 81
lastpage: 96
origpdf: http://jmlr.org/proceedings/papers/v20/ishihata11/ishihata11.pdf
sections: 
authors:
- given: M.
  family: Ishihata
- given: T.
  family: Sato
---
