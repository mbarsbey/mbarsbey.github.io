---
layout: post
title: Research
published: true
---


I am a computer engineering PhD student with a focus on probabilistic machine learning. My research areas comprise of **causal inference, model selection, and latent variable modeling**. 

My advisor is Prof. **A. Taylan Cemgil** of Bogazici University, Istanbul. I have industry experience as a data scientist in time series analysis and high dimensional financial data. I also have a background in experiment design, research, and statistical inference in cognitive science.

Below are some excerpts from my past work. Feel free to visit my GitHub page, my LinkedIn profile, and to e-mail me through melih.barsbey at gmail.com for any questions.

## Causal discovery using Bayesian model selection

Our latest research involves the **use of Bayesian model selection to conduct causal structure learning** in the presence of latent confounders, including the notorious case of bivariate data. For example, distinguishing between the three graphical models depicted below is a challanging task, given that the last two are Markov equivalent.

![_config.yml]({{ site.baseurl }}/images/three_causal_hypotheses.png)

We also use Bayesian inference to obtain confounder representations (e.g. by sampling from the posterior distribution of the latent confounder) and to produce counterfactual predictions.

## Model selection in graphical models through sequential Monte Carlo

We use a dynamic formulation of Bayesian networks with discrete data, which corresponds to a **Polya urn process**. Our formulation allows us to develop a sequential Monte Carlo algorithm with which we can conduct model selection through an **unbiased estimation of marginal likelihood** in arbitrary Bayesian networks including those which correspond to various topic models and tensor factorizations. 

![_config.yml]({{ site.baseurl }}/images/polya.png)

The estimator also has the favorable property of computationally scaling with the number of instances as opposed to methods like VB, which scale with the cardinality of the variables. This feature makes the method favorable especially in cases such as decomposition of large, sparse tensors.

## Industry projects

I have worked for two years as a data scientist in a software consultancy start-up in the financial sector. I have conducted time series analysis on financial data extensively where I was the lead developer of an ATM cash management forecast engine that managed approximately 8000 ATMs daily. 

I have lead a team of 5 data scientists onto a successful branch cash management proof of concept for a major Turkish bank with more than 800 branches, leading to savings of more than 30%. There I also oversaw the development of a simulation engine for what-if scenarios, which successfully predicted the savings obtained later. 

I have also conducted statistical learning on high dimensional financial and business data sets: e.g.  behavior oriented dimensionality reduction on bank customer interaction data, Bayesian modeling of customer call success for a bank's call center, and employee churn prediction for a high turnover business.

## Background in behavioral and cognitive science



Images courtesy of BAM Research Group.