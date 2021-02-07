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

LingPipe is a Java API for natural language processing applications.  It does L1-regularized classifctaion with general priors and stochastic gradient descent, sequence models with HMMs and conditional random fields, clustering with Gibbs-sampled LDA and expectation maximization K-means, sequence chunking named-entity detection and Chinese word segmentation, noisy channel spelling correction, and token-level and character-level language modeling.  There's thorough documentation and a wide range of tutorials with applications in multiple languages.  Designed to run on the server side.  Deployed to back a wide range of commercial applications.  AGPL licensed.

* [LingPipe](http://www.alias-i.com/lingpipe/)

I wrote pretty much all of this while working at Alias-i.  It had a non-standard AGPL-like license before switcing to AGPL.


## Attribute Logic Engine (ALE)

The Attribute Logic Engine was written in support of my [book on typed feature structures]( https://www.amazon.com/Logic-Typed-Feature-Structures-Applications/dp/0521022541).  It is a logic programming, constraint satisfaction, and unification-grammar parser with typed feature structures.  Coded in Prolog and distributed as freeware.

* [ALE](http://www.cs.toronto.edu/~gpenn/ale.html)

I wrote the prototype version and the first manual, then Gerald Penn took it over, extended it, and maintained it.


## Older projects

My first memory of open-source software was sharing Prolog parsers for Lambek-style categrorial grammars.  I once distributed a Prolog-backed CGI gateway along with a parser for my second book that converted input to LaTeX output and rendered it;  someone in the Netherlands maintained it long after I'd left the field.
