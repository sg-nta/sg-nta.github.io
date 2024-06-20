---
title: "On Robust Optimal Transport: Computational
Complexity and Barycenter Computation"
category: articles
permalink: "/publications/ROT/"
venue: "35th Conference on Neural Information Processing Systems (NeurIPS)"
date: 06-12-2021
link: https://arxiv.org/abs/2102.06857
---

[comment]: <> (<a href="https://arxiv.org/pdf/2102.06857.pdf">Arxiv</a>.)
<b>Huy Nguyen\*</b>, Khang Le\*, Quang Minh Nguyen, Tung Pham, Hung Bui, Nhat Ho

Abstract: We consider two robust versions of optimal transport, named Robust Semi-constrained Optimal Transport (RSOT) and Robust Unconstrained Optimal Transport (ROT), formulated by relaxing the marginal constraints with Kullback-Leibler divergence. For both problems in the discrete settings, we propose Sinkhorn-based algorithms that produce ε-approximations of RSOT and ROT in O˜(n2ε) time, where n is the number of supports of the probability distributions. Furthermore, to reduce the dependency of the complexity of the Sinkhorn-based algorithms on n, we apply Nyström method to approximate the kernel matrix in both RSOT and ROT by a matrix of rank r before passing it to these Sinkhorn-based algorithms. We demonstrate that these new algorithms have O˜(nr2+nrε) runtime to obtain the RSOT and ROT ε-approximations. Finally, we consider a barycenter problem based on RSOT, named Robust Semi-Constrained Barycenter problem (RSBP), and develop a robust iterative Bregman projection algorithm, called Normalized-RobustIBP algorithm, to solve the RSBP in the discrete settings of probability distributions. We show that an ε-approximated solution of the RSBP can be achieved in O˜(mn2ε) time using Normalized-RobustIBP algorithm when m=2, which is better than the previous complexity O˜(mn2ε2) of IBP algorithm for approximating the Wasserstein barycenter. Extensive experiments confirm our theoretical results.

