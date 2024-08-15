---
title: "Identifying Invariant Factors Across Multiple Environments with KL Regression"
collection: publications
permalink: /publication/2020-02-kl-regression
excerpt: 'We tackle here the problem of irreproducibility due to distribution shift. We develop a new approach to regression where datasets from different sources become data points in a regression where parametrization is done for distribution shifts. This allows us to estimate the causal invariant parameters shared across all distributions.'
date: 2020-02-01
paperurl: 'https://arxiv.org/abs/2002.08341'
citation: 'Jaime Roquero Gimenez, and James Zou. "Identifying Invariant Factors Across Multiple Environments with KL Regression." ArXiv pre-print (2020).'
image: 'kl_regression.png'
---

Many datasets are collected from multiple environments (e.g. different labs, perturbations, etc.), and it is often advantageous to learn models and relations that are invariant across environments. Invariance can improve robustness to unknown confounders and improve generalization to new domains. We develop a novel framework -- KL regression -- to reliably estimate regression coefficients in a challenging multi-environment setting, where latent confounders affect the data from each environment. KL regression is based on a new objective of simultaneously minimizing the KL- divergence between a parametric model and the observed data from each environment. We prove that KL regression recovers the true invariant factors under a flexible confounding setup. Moreover, it is computationally efficient as we derive an analytic solution for its global optimum. In systematic experiments, we validate the improved performance of KL regression compared to commonly used approaches.

[Paper](https://arxiv.org/abs/2002.08341) \| [Code](https://github.com/jroquerogimenez/Code_DGM)


