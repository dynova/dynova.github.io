---
title: "Implementation of a practical Markov chain Monte Carlo sampling algorithm in PyBioNetFit"
collection: publications
permalink: /publications/neumann_posner_bioinformatics2022
excerpt: ''
date: 2022-03-15
venue: 'Bioinformatics'
paperurl: 'https://academic.oup.com/bioinformatics/article-pdf/38/6/1770/49692951/btac004.pdf'
citation: 'Neumann, J., Lin, Y.T., <b>Mallela, A.</b>, Miller, E.F., Colvin, J., Duprat, A.T., Chen, Y., Hlavacek, W.S., and Posner, R.G.'
---

# Abstract 
Bayesian inference in biological modeling commonly relies on Markov chain Monte Carlo (MCMC) sampling of a multidimensional and non-Gaussian posterior distribution that is not analytically tractable. Here, we present the implementation of a practical MCMC method in the open-source software package PyBioNetFit (PyBNF), which is designed to support parameterization of mathematical models for biological systems. The new MCMC method, am, incorporates an adaptive move proposal distribution. For warm starts, sampling can be initiated at a specified location in parameter space and with a multivariate Gaussian proposal distribution defined initially by a specified covariance matrix. Multiple chains can be generated in parallel using a computer cluster. We demonstrate that am can be used to successfully solve real-world Bayesian inference problems, including forecasting of new Coronavirus Disease 2019 case detection with Bayesian quantification of forecast uncertainty.