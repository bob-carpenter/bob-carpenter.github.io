---
layout: archive
title: "Projects"
permalink: /projs/
author_profile: true
---

{% include base_path %}

Almost all of my projects are cooperative;  if you'd like to get
involved in one of these projects or have another project in mind,
please let me know.


## Stan

My main project is Stan, where I'm primarily involved with the
language design and automatic differentiation library.

### Language design

* *Language constructs*: tuples and structs (with Ryan Bernstein); complex numbers,
  arithmetic, matrices, and functions (with Steve Bronder, completed
  math library last year); first-class functions and closures (with
  Niiko Huure); immutable matrices (with Steve Bronder, Rok Češnovar,
  Tadej Ciglarič); stacked bijectors; ragged arrays; comprehensions;
  covariant containers

* *Formal specification and verification* (with Ryan Bernstein,
  Matthijs Vákár, Maria Gorinova, Jean-Baptiste Tristan, Brian Ward):
  operational semantics and verified parser

### Algorithms

* *Pathfinder* (with Lu Zhang, Ben Bales, Andrew Gelman, Aki Vehtari):
  parallel burn-in to find first reasonable draw;  stacks with 
  parallel covariance adaptation (Ben Bales, Yi Zhang) and embarrassingly parallel
  MCMC 

* *Hamiltonian integrators* for stiff and oscillatory Hamiltonians (with Chirag Modi,
  Alex Barnett)---looking into variable stepsize leapfrog and implicit
  midpoint to start

### Math library

* *Complex numbers*: complex/primitive mixed matrix operations (with Steve Bronder);
expose FFT, asymmetric eigenvalues as functions

### Testing

* *Automatic differentiation testing*: automate to higher tolerance (with Adam Huber)

* *PosteriorDB*: scale database of reference posteriors; write-up
  application methodology (with Måns Magnusson, Aki Vehtari)

### Documentation

* *User's Guide*: bring up to best practices for Stan 3.0

### Interfaces

* *Stan IDE*: visual environment for running Stan programs and
monitoring their progress---auto-adaptation convergence, auto
effective sample size targets, visual progress monitoring and
checkpointing


## Books

* *Bayesian Workflow*: a book about how we actually fit models
  including worked examples;  long article written, open-access
  contract with CRC (with Andrew Gelman, Aki Vehtari, Daniel Simpson,
  Charles C. Margossian, Bob Carpenter, Yuling Yao, Lauren Kennedy
  Jonah Gabry, Paul-Christian Bürkner, Martin Modrák)


* *Probability and Statistics: A simulation-based approach*:
  upper-level undergraduate book for applied statisticians to replace
  the usual frequentist/calculus-based book with one based on
  sampling; also covers basics of Bayesian statistics and statistical
  computation

* *Automatic Differentiation Handbook* intro to forward- and
  reverse-mode autodiff with matrix results and adjoint derivations
  for optimizers, ODE solvers, and HMMs (with Adam Haber, Charles
  Margossian)


## Applied Statistics

* *Genomics: differential expression*: multilevel Bayesian
differential isoform expression with replication (with Shuonan Chen,
Chaolin Zhang); K-mer based gene expression from RNA-seq data without
alignment or assignment (prototype stage)

* *Covid prevalence*: working with UK Biosecurity Centre to monitor
  prevalence over time and location and adjust for non-random testing
  sample (with Tom Ward, Alexander Johnsen, Andrew Gelman, Mitzi
  Morris)

* *Multilevel continuous time series with Chebyshev coefficients*:
parameterizing general function fitting (with Philip Greengard)

* *Data coding and crowdsourcing*: continuing my work on crowdsourcing
  to account for item difficulty and multivariate responses (I've
  worked on this problem with many people over time including
  Breck Baldwin, Mitzi Morris, Becky Passonneau, Massimo Poesio, and
  Silviu Paun) including everything from statistical inference to
  tag-a-little/learn-a-little interactive interfaces.

* *Soil carbon modeling*: continuing work on compartmental ODEs for
  soil carbon sequestration and respiration, adapting to enzyme models
  and other complex forward scientific models (with Kathe Todd-Brown)



