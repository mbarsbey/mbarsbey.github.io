---
layout: post
title: Research
published: true
---


I am a Computer Engineering PhD student with a focus on probabilistic machine learning. My research areas include **causal inference, model selection, and latent variable modeling**. My advisor is **Prof. A. Taylan Cemgil** of Bogazici University, Istanbul. 

I also have industry experience as a data scientist in **time series analysis** and statistical learning in **high dimensional financial data**; as well as a background in experiment design, research, and statistical inference in **cognitive science**.

Below are my publications and some excerpts from my past work. Feel free to visit my <a href="github.com/mbarsbey">GitHub page</a>, my <a href="www.linkedin.com/in/melih-barsbey">LinkedIn profile</a>, or to e-mail me through _melih.barsbey at gmail.com_ for any questions.


## Recent Submissions

- Kurutmaz, M. B.\*, **Barsbey, M.\***, Cemgil, A. T., Yıldırım, S., & Şimşekli, U. _Causal Structure Learning in the Presence of Latent Confounders_, submitted to _Advances in Neural Information Processing Systems_, 2019. \*Equal contribution
- Cemgil, A. T., Kurutmaz, M. B., Yildirim, S., **Barsbey, M.**, Simsekli, U. _Bayesian Allocation Model: Model Selection for Graphical Models with Latent Variables using Polya Urns_, submitted to _Bayesian Analysis_, 2019.  

See my CV from the link above for full list of publications.

## Excerpts from current work
### Causal discovery using Bayesian model selection

Our latest research involves the **use of Bayesian model selection to conduct causal structure learning** in the presence of latent confounders, including the notorious case of bivariate data. For example, distinguishing between the three graphical models depicted below is a challanging task. It corresponds to detection of direction of causation (or lack thereof) between two observed variables, while accounting for an unobserved latent variable:

![_config.yml]({{ site.baseurl }}/images/three_causal_hypotheses.png)

We are currently furthering our work by using Bayesian inference to obtain confounder representations (e.g. by sampling from the posterior distribution of the latent confounder) and to produce counterfactual predictions on the individual level.

### Model selection in graphical models by sequential Monte Carlo

We develop a dynamic generative allocation model, in which allocations are made according to a Bayesian network, and marginals of which correspond to a **Polya urn process**. Our formulation allows us to develop a sequential Monte Carlo algorithm with which we can conduct model selection through an **unbiased estimation of marginal likelihood** in arbitrary Bayesian networks including those which correspond to various topic models and tensor factorizations. 

![_config.yml]({{ site.baseurl }}/images/polya_s.png)

The estimator also has the favorable property of computationally scaling with the number of instances as opposed to methods like VB, which scale with the cardinality of the variables. This feature makes the method favorable especially in cases such as decomposition of large, sparse tensors.

### Industry projects

I have worked for two years as a data scientist in a software consultancy start-up in the financial sector. I have conducted **time series analysis** on financial data extensively, where I was the lead developer of an **ATM cash management forecast engine** that managed approximately **8000 ATMs daily**. 

I have **lead a team of 5 data scientists** in a successful branch cash management proof of concept for a major Turkish bank, leading to **savings of more than 30%**. There I also oversaw the development of **a simulation engine for what-if scenarios**, which successfully predicted the savings obtained later. 

I have also conducted statistical learning on **high dimensional financial and business data sets**: e.g.  behavior oriented dimensionality reduction on bank customer interaction data, Bayesian modeling of customer call success for a bank's call center, and employee churn prediction for a high turnover business.

### Background in behavioral and cognitive science

I have also extensive experience with experiment design and statistical inference in **cognitive science**. In my master's research I conducted on an experimental investigation on the **mental representations of textual narratives**. In my research visit to **UC Berkeley's Concepts and Cognition Lab**, I have conducted research on the **cognitive science of explanations**. I have also taught introductory statistics courses for psychology students that included **descriptive and inferential statistical methods** for social sciences.

In a work presented at the Summer Institute on Bounded Rationality in **Max Planck Institute on Human Development** I have presented exploratory work to investigate the effect of model complexity on survival in high uncertainty environments, using **agent-based modeling.**



_Images courtesy of BAM Research Group_
