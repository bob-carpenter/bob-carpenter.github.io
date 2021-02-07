---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Here are some projects that still have useful code.

## Stan

Stan is a probabilistic programming language that lets users define a probabilistic model, translates it to C++, then performs Bayesian inference with Markov chain Monte Carlo, automatic differentiation variational inference, or Laplace approximations.  Stan is used across the physical, biological, and social sciences, as well as in finance, government, medicine, policy, and leisure.  It runs on all platforms and has interfaces in R, Python, Julia, MATLAB, and Mathematica.  BSD-3 licensed.

* [Stan](https://mc-stan.org)

I was the co-founder of the project and designer of the probabilistic programming language and automatic differentiation library.  I've also written most of the language documentation.  By version 1.0, we had seven developers, and we now have more than forty.
The language code has been completely rewritten from scratch in OCaml.

## pyAnno

Lightweight Python package implementing expectation-maximization for MAP estimation of Dawid and Skene's model of crowdsourced data annotation extended with priors.  BSD-2 licensed.

* [PyAnno](https://pypi.org/project/pyanno/)

I wrote the inference code and then Enthought did the package wrapper and now maintain it.


## LingPipe

LingPipe is a server-side Java API for multilingual natural language processing applications.  It fits MAP estimates for L1-regularized classification and conditional random fields with L1, L2, and mixed penalties with stochastic gradient descent.  It also supports HMMs, hierarchical, K-means, and LDA clustering, sequence chunking for named entity extraction and Chinese word segmenation, noisy channel spelling correction, and token- and character-level language modeling.  AGPL licensed.

* [LingPipe](http://www.alias-i.com/lingpipe/)

I wrote pretty much all of this while working at Alias-i, because of its non-standard AGPL-like license. 


## Attribute Logic Engine (ALE)

The Attribute Logic Engine was written in support of my [book on typed feature structures]( https://www.amazon.com/Logic-Typed-Feature-Structures-Applications/dp/0521022541).  It provides is a logic programming language, constraint solver and unification grammar backed by inheritance-based structure types.  Coded in Prolog and distributed as freeware.

* [ALE](http://www.cs.toronto.edu/~gpenn/ale.html)

I wrote the prototype version and the first manual.


## Older projects

In the early 2000s at SpeechWorks, I worked on open speech interface standards and distributed VoiceXML-backed games.  As a professor in the 1990s, I distributed Prolog code for my computational linguistics classes.  In grad school in the mid-1980s, we shared backtracking categorial grammar parsers in Prolog and chart parsers in Lisp via FTP.  I built an [arithmetic coder in Java](https://github.com/bob-carpenter/java-arithcode) using PPM compression (based on C code by Radford Neal) so I could show prospective employers code after working on proprietary speech recognizers at SpeechWorks.  After a short plane ride on which I solved my first Sudoku by hand, I wrote and distributed [a backtracking Sudoku solver in Java](https://github.com/bob-carpenter/java-sudoku).
