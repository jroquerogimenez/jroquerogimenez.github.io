---
title: "Improving the Stability of the Knockoff Procedure: Multiple Simultaneous Knockoffs and Entropy Maximization"
collection: publications
permalink: /publication/2018-10-multiknockoffs
excerpt: 'Stabilizing the knockoff procedure through a novel multiple knockoff sampling approach and an improved optimization problem in the Gaussian case.'
date: 2019-04-01
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'http://proceedings.mlr.press/v89/gimenez19b/gimenez19b.pdf'
citation: 'Jaime Roquero Gimenez, and James Zou. "Improving the stability of the knockoff procedure: Multiple simultaneous knockoffs and entropy maximization." In The 22nd international conference on artificial intelligence and statistics, pp. 2184-2192. PMLR, 2019.'
image: 'multiknockoffs.png'
---

The Model-X knockoff procedure has recently emerged as a powerful approach for feature selection with statistical guarantees. The advantage of knockoff is that if we have a good model of the features X, then we can identify salient features without knowing anything about how the outcome Y depends on X. An important drawback of knockoffs is its instability: running the procedure twice can result in very different selected features, potentially leading to different conclusions. Addressing this instability is critical for obtaining reproducible and robust results. Here we present a generalization of the knockoff procedure that we call simultaneous multi-knockoffs. We show that multi-knockoff guarantees false discovery rate (FDR) control, and is substantially more stable and powerful compared to the standard (single) knockoff. Moreover we propose a new algorithm based on entropy maximization for generating Gaussian multi-knockoffs. We validate the improved stability and power of multi-knockoffs in systematic experiments. We also illustrate how multi-knockoffs can improve the accuracy of detecting genetic mutations that are causally linked to phenotypes.

[Paper](http://proceedings.mlr.press/v89/gimenez19b/gimenez19b.pdf) \| [Supplement](http://proceedings.mlr.press/v89/gimenez19b/gimenez19b-supp.pdf) \| [Code](https://github.com/jroquerogimenez/Code_DGM)


