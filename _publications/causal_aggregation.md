---
title: "Causal aggregation: estimation and inference of causal effects by constraint-based data fusion"
collection: publications
permalink: /publication/2021-06-causal-aggregation
excerpt: 'We build a causal estimator by aggregating information from different sources of data where experimental conditions are different, and assumptions on the causal relationship between variables can vary.'
date: 2022-01-01
venue: 'Journal of Machine Learning Research (JMLR)'
paperurl: 'https://www.jmlr.org/papers/volume23/21-0656/21-0656.pdf'
citation: 'Jaime Roquero Gimenez and Dominik Rothenhäusler. "Causal aggregation: estimation and inference of causal effects by constraint-based data fusion." Journal of Machine Learning Research 23, no. 335 (2022): 1-60.'
image: 'causal_aggregation.png'
---

In causal inference, it is common to estimate the causal effect of a single treatment variable on an outcome. However, practitioners may also be interested in the effect of simultaneous interventions on multiple covariates of a fixed target variable. We propose a novel method that allows to estimate the effect of joint interventions using data from different experiments in which only very few variables are manipulated. If there is only little randomized data or no randomized data at all, one can use observational data sets if certain parental sets are known or instrumental variables are available. If the joint causal effect is linear, the proposed method can be used for estimation and inference of joint causal effects, and we characterize conditions for identifiability. In the overidentified case, we indicate how to leverage all the available causal information across multiple data sets to efficiently estimate the causal effects. If the dimension of the covariate vector is large, we may only have a few samples in each data set. Under a sparsity assumption, we derive an estimator of the causal effects in this high-dimensional scenario. In addition, we show how to deal with the case where a lack of experimental constraints prevents direct estimation of the causal effects. When the joint causal effects are non-linear, we characterize conditions under which identifiability holds, and propose a non-linear causal aggregation methodology for experimental data sets similar to the gradient boosting algorithm where in each iteration we combine weak learners trained on different datasets using only unconfounded samples. We demonstrate the effectiveness of the proposed method on simulated and semi-synthetic data.

[Paper](https://www.jmlr.org/papers/volume23/21-0656/21-0656.pdf) \| [Code](https://github.com/jroquerogimenez/CausalAggregation)

