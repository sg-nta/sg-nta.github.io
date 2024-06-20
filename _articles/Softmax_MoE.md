---
title: "Demystifying Softmax Gating Function in Gaussian Mixture of Experts"
category: articles
permalink: "/publications/Softmax_MoE/"
venue: "37th Conference on Neural Information Processing Systems (NeurIPS)"
date: 25-09-2023
link: https://arxiv.org/abs/2305.03288
---

[comment]: <> (<a href="https://arxiv.org/abs/2305.03288">Arxiv</a>.)
<b>Huy Nguyen</b>, TrungTin Nguyen, Nhat Ho

Abstract: Understanding parameter estimation of softmax gating Gaussian mixture of experts has
remained a long-standing open problem in the literature. It is mainly due to three fundamental
theoretical challenges associated with the softmax gating: (i) the identifiability only up to
the translation of the parameters; (ii) the intrinsic interaction via partial differential equation
between the softmax gating and the expert functions in Gaussian distribution; (iii) the complex
dependence between the numerator and denominator of the conditional density of softmax gating
Gaussian mixture of experts. We resolve these challenges by proposing novel Vononoi loss
functions among parameters and establishing the convergence rates of the maximum likelihood
estimator (MLE) for solving parameter estimation in these models. When the number of experts
is unknown and over-specified, our findings show a connection between the rate of MLE and a
solvability problem of a system of polynomial equations.
