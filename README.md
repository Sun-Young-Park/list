# R package list
[![Travis-CI Build Status](https://travis-ci.org/SensitiveQuestions/list.svg?branch=master)](https://travis-ci.org/SensitiveQuestions/list) [![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/list)](https://cran.r-project.org/package=list)

This package allows researchers to conduct multivariate
    statistical analyses of survey data with list experiments. This
    survey methodology is also known as the item count technique or
    the unmatched count technique and is an alternative to the commonly
    used randomized response method. The package implements the methods
    developed by [Imai (2011)](https://doi.org/10.1198/jasa.2011.ap10415), 
    [Blair and Imai (2012)](https://doi.org/10.1093/pan/mpr048), 
    [Blair, Imai, and Lyall (2013)](https://doi.org/10.1111/ajps.12086), 
    [Imai, Park, and Greene (2014)](https://doi.org/10.1093/pan/mpu017),
    [Aronow, Coppock, Crawford, and Green (2015)](https://doi.org/10.1093/jssam/smu023), 
    and [Chou, Imai, and Rosenfeld (2016)](http://imai.princeton.edu/research/files/auxiliary.pdf). 
    This includes a Bayesian MCMC implementation of regression for the 
    standard and multiple sensitive item list experiment designs and a 
    random effects setup, a Bayesian MCMC hierarchical regression model 
    with up to three hierarchical groups, the combined list experiment 
    and endorsement experiment regression model, a joint model of the 
    list experiment that enables the analysis of the list experiment as 
    a predictor in outcome regression models, and a method for combining 
    list experiments with direct questions. In addition, the package
    implements the statistical test that is designed to detect
    certain failures of list experiments, and a placebo test
    for the list experiment using data from direct questions.
