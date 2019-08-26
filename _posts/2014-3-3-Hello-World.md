---
layout: post
title: Research
published: true
---


I am a computer engineering PhD student with a focus on probabilistic machine learning. My research areas comprise of **causal inference, model selection, and latent variable modeling**. My advisor is Prof. A. Taylan Cemgil of Bogazici University, Istanbul. I have industry experience as a data scientist in time series analysis and high dimensional financial data. I also have a background in experiment design, research, and statistical inference in cognitive science.

## Causal discovery using Bayesian model selection

Our latest research involves the **use of Bayesian model selection to conduct causal structure learning** in the presence of latent confounders, including the notorious case of bivariate data. For example, distinguishing between the three graphical models depicted below is a challanging task, given that the last two are Markov equivalent.

![_config.yml]({{ site.baseurl }}/images/three_causal_hypotheses.png)

We also use Bayesian inference to obtain confounder representations (e.g. by sampling from the posterior distribution of the latent confounder) and to produce counterfactual predictions.

## Using sequential Monte Carlo sampling to conduct model selection in graphical models

We use a dynamic formulation of Bayesian networks with discrete data, which corresponds to a simple Polya urn process. Our formulation allows us to develop a sequential Monte Carlo algorithm with which we can conduct model selection through an unbiased estimation of marginal likelihood in Bayesian networks including topic models and tensor factorizations. 



The estimator also has the favorable property of computationally scaling with the number of instances as opposed to methods like VB, which scale with the cardinality of the variables. This feature makes the method favorable especially in cases such as decomposition of large, sparse tensors.

## Examining the relationship between model complexity vs. environment uncertainty using agent based modeling

This exploratory project aimed to recreate the oft-cited claim in the field of 



Images courtesy of BAM Research Group.