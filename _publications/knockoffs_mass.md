---
title: "Knockoffs for the mass: new feature importance statistics with false discovery guarantees"
collection: publications
permalink: /publication/2018-07-knockoffs-for-the-mass
excerpt: 'This work introduces novel methods for building knockoffs from a wide range of covariate distributions beyond multivariate Gaussian.'
date: 2019-04-01
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'http://proceedings.mlr.press/v89/gimenez19a/gimenez19a.pdf'
citation: 'Jaime Roquero Gimenez, Amirata Ghorbani, and James Zou. "Knockoffs for the mass: new feature importance statistics with false discovery guarantees." In The 22nd international conference on artificial intelligence and statistics, pp. 2125-2133. PMLR, 2019.'
image: 'knockoffs_mass.png'
---

An important problem in machine learning and statistics is to identify features that causally affect the outcome. This is often impossible to do from purely observational data, and a natural relaxation is to identify features that are correlated with the outcome even conditioned on all other observed features. For example, we want to identify that smoking really is correlated with cancer conditioned on demographics. The knockoff procedure is a recent breakthrough in statistics that, in theory, can identify truly correlated features while guaranteeing that false discovery rate is controlled. The idea is to create synthetic data-knockoffs-that capture correlations among the features. However, there are substantial computational and practical challenges to generating and using knockoffs. This paper makes several key advances that enable knockoff application to be more efficient and powerful. We develop an efficient algorithm to generate valid knockoffs from Bayesian Networks. Then we systematically evaluate knockoff test statistics and develop new statistics with improved power. The paper combines new mathematical guarantees with systematic experiments on real and synthetic data.

[Paper](http://proceedings.mlr.press/v89/gimenez19a/gimenez19a.pdf) \| [Supplement](http://proceedings.mlr.press/v89/gimenez19a/gimenez19a-supp.pdf) \| [Code](https://github.com/jroquerogimenez/Code_DGM)


