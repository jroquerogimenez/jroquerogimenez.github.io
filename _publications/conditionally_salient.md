---
title: "Discovering conditionally salient features with statistical guarantees"
collection: publications
permalink: /publication/2019-05-conditionally-salient
excerpt: 'Stabilizing the knockoff procedure through a novel multiple knockoff sampling approach and an improved optimization problem in the Gaussian case.'
date: 2019-04-01
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'http://proceedings.mlr.press/v89/gimenez19b/gimenez19b.pdf'
citation: 'Jaime Roquero Gimenez, and James Zou. "Discovering conditionally salient features with statistical guarantees." In International conference on machine learning, pp. 2290-2298. PMLR, 2019.'
image: 'multiknockoffs.png'
---

The goal of feature selection is to identify important features that are relevant to explain an outcome variable. Most of the work in this domain has focused on identifying globally relevant features, which are features that are related to the outcome using evidence across the entire dataset. We study a more fine-grained statistical problem: conditional feature selection, where a feature may be relevant depending on the values of the other features. For example in genetic association studies, variant A could be associated with the phenotype in the entire dataset, but conditioned on variant B being present it might be independent of the phenotype. In this sense, variant A is globally relevant, but conditioned on B it is no longer locally relevant in that region of the feature space. We present a generalization of the knockoff procedure that performs conditional feature selection while controlling a generalization of the false discovery rate (FDR) to the conditional setting. By exploiting the feature/response model-free framework of the knockoffs, the quality of the statistical FDR guarantee is not degraded even when we perform conditional feature selections. We implement this method and present an algorithm that automatically partitions the feature space such that it enhances the differences between selected sets in different regions, and validate the statistical theoretical results with experiments.

[Paper](http://proceedings.mlr.press/v89/gimenez19b/gimenez19b.pdf) \| [Supplement](http://proceedings.mlr.press/v89/gimenez19b/gimenez19b-supp.pdf) \| [Code](https://github.com/jroquerogimenez/Code_DGM)

