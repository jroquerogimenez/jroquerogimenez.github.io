---
title: "A Unified f-divergence Framework Generalizing VAE and GAN"
collection: publications
permalink: /publication/2022-05-f-divergence
excerpt: 'We define a generalization of the Variational Auto-Encoder and Generative Adversarial network by redefining the loss through f-divergences.'
paperurl: 'https://arxiv.org/abs/2205.05214'
citation: 'Jaime Roquero Gimenez, and James Zou. "Identifying Invariant Factors Across Multiple Environments with KL Regression." ArXiv pre-print. Accepted at ISIT 2022.'
image: 'f-divergence.png'
---

Developing deep generative models that flexibly incorporate diverse measures of probability distance is an important area of research. Here we develop an unified mathematical framework of f-divergence generative model, f-GM, that incorporates both VAE and f-GAN, and enables tractable learning with general f-divergences. f-GM allows the experimenter to flexibly design the f-divergence function without changing the structure of the networks or the learning procedure. f-GM jointly models three components: a generator, a inference network and a density estimator. Therefore it simultaneously enables sampling, posterior inference of the latent variable as well as evaluation of the likelihood of an arbitrary datum. f-GM belongs to the class of encoder-decoder GANs: our density estimator can be interpreted as playing the role of a discriminator between samples in the joint space of latent code and observed space. We prove that f-GM naturally simplifies to the standard VAE and to f-GAN as special cases, and illustrates the connections between different encoder-decoder GAN architectures. f-GM is compatible with general network architecture and optimizer. We leverage it to experimentally explore the effects -- e.g. mode collapse and image sharpness -- of different choices of f-divergence.

[Paper](https://arxiv.org/abs/2205.05214) \| [Code](https://github.com/jroquerogimenez/Code_DGM)


