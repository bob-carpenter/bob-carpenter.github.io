---
layout: archive
title: "Projects"
permalink: /projs/
author_profile: true
---
{% include base_path %}
If you'd like to get involved in one of these projects or have another project in mind, please let me know.  My research is in computational statistics algorithms and applied statistics methodology. I work on development for Stan's probabilistic programming language and automatic differentiation library.


## Algorithms
### Parallel Hamiltonian Monte Carlo
HMC sampling is embarrassingly parallelizable after stationarity;  the sequential bottlenecks are finding the first reasonable draw and adapting to posterior covariance.
* *Pathfinder*: parallel algorithm to find first reasonable draw; with Lu Zhang, Ben Bales, Aki Vehtari, Andrew Gelman
* *parallel covariance adaptation*: needs engineering for Stan; led by Ben Bales, Yi Zhang
* *embarrassingly parallel MCMC*:  trivial given random draw and adaptation


### Integrators for stiff Hamiltonians
The potential energy field induced by the negative log posterior can have varying curvature beyond the ability of a Euclidean metric to compensate, inducing stiffness in the leapfrog integrator and causing HMC to mix poorly.
* *integrators for stiff Hamiltonians*: initially exploring variable stepsize leapfrog and implicit midpoint integrators; with Chirag Modi, Alex Barnett


## Stan
### Language design
The heart of Stan is its probabilistic programming language.  My main development project is enhancing the language.
* *Language constructs*
    * *tuples and structs*: design complete, prototyped; with Ryan Bernstein
    * *complex numbers*:  needs final design; with Steve Bronder
    * *first-class functions and closures*; prototyped; with Niiko Huure
	* *immutable matrices*: pro-typed; with Steve Bronder, Rok Češnovar
	* *stacked bijectors*: design complete
	* *ragged arrays*: design complete
	* *covariant containers*: design complete
	* *comprehensions*: awaiting design

* *Formal specification and verification*
    * *Operational semantics*: core drafted; with Ryan Bernstein, Matthijs Vákár, Maria Gorinova
	* *Verification*: prototyped; tangentially involved with Jean-Baptiste Tristan

### Automatic differentiation library
* *Complex numbers*: complex/primitive mixed matrix operations, expose FFT, asymmetric eigenvalues as functions; with Steve Bronder
* *Automatic differentiation testing*: automate to higher tolerance (with Adam Huber)
* *Immutable matrices*: led by Ben Bales, Steve Bronder, Tadej Ciglarič, Rok Češnovar

### Testing
* *PosteriorDB*: scale database of reference posteriors; write-up application methodology; led by Måns Magnusson, Aki Vehtari

### Documentation
* *User's Guide*: bring up to best practices for Stan 3.0
* *Gentle introduction to Stan*: needs to be written

### Interfaces
* *Stan IDE*: visual environment for running Stan programs and monitoring their progress---auto-adaptation convergence, auto effective sample size targets, visual progress monitoring and checkpointing; needs design and evaluation


## Books
* *Bayesian Workflow*: a book about how we actually fit models including worked examples; long article written, open-access contract with CRC; with Andrew Gelman, Aki Vehtari, Daniel Simpson, Charles C. Margossian, Bob Carpenter, Yuling Yao, Lauren Kennedy Jonah Gabry, Paul-Christian Bürkner, Martin Modrák
* *Probability and Statistics: A simulation-based approach*: upper-level undergraduate book for applied statisticians to replace the usual frequentist/calculus-based book with one based on sampling; also covers basics of Bayesian statistics and statistical computation
* *Automatic Differentiation Handbook* intro to forward- and reverse-mode autodiff with matrix results and adjoint derivations for optimizers, ODE solvers, and HMMs (with Adam Haber, Charles Margossian)


## Applied Statistics
* *Genomics: differential expression*
    * *multilevel Bayesian differential isoform expression with
      replication*;  with Shuonan Chen, Chaolin Zhang;
	* *K-mer based gene expression from RNA-seq data without
alignment or assignment*; designed, prototype begun
* *UK Covid biosurveillance*: working with UK Biosecurity Centre to monitor
  prevalence over time and location and adjust for non-random testing
  sample; with Tom Ward, Alexander Johnsen, Andrew Gelman, Mitzi
  Morris
* *Multilevel continuous time series with Chebyshev coefficients*:
parameterizing general function fitting; with Philip Greengard
* *Data coding and crowdsourcing*:
    * *difficulty*: continuing my work on crowdsourcing
	to account for item difficulty using IRT-like models
	* *multivariate response*: extend binary IRT-like model of difficulty
    * *deep neural networks*: would like to find a way to train neural
      nets to evaluate the effect of regularization
* *Soil carbon modeling*: continuing work on compartmental ODEs for
  soil carbon sequestration and respiration, adapting to enzyme models
  and other complex forward scientific models (with Kathe Todd-Brown)



