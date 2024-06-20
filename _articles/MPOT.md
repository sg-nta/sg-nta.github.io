---
title: "On Multimarginal Partial Optimal Transport: Equivalent Forms and Computational Complexity"
category: articles
permalink: "/publications/MPOT/"
venue: "25th International Conference on Artificial Intelligence and Statistics (AISTATS)"
date: 28-03-2022
link: https://proceedings.mlr.press/v151/le22a.html
---

[comment]: <> (<a href="https://proceedings.mlr.press/v151/le22a.html">Arxiv</a>.)
<b>Huy Nguyen\*</b>, Khang Le\*, Khai Nguyen, Tung Pham, Nhat Ho

Abstract: We study the multi-marginal partial optimal transport (POT) problem between m discrete
(unbalanced) measures with at most n supports. We first prove that we can obtain two equivalence
forms of the multimarginal POT problem in terms of the multimarginal optimal transport problem
via novel extensions of cost tensor. The first equivalence form is derived under the assumptions
that the total masses of each measure are sufficiently close while the second equivalence form does
not require any conditions on these masses but at the price of more sophisticated extended cost
tensor. Our proof techniques for obtaining these equivalence forms rely on novel procedures of
moving mass in graph theory to push transportation plan into appropriate regions. Finally, based
on the equivalence forms, we develop optimization algorithm, named ApproxMPOT algorithm,
that builds upon the Sinkhorn algorithm for solving the entropic regularized multimarginal
optimal transport. We demonstrate that the ApproxMPOT algorithm can approximate the
optimal value of multimarginal POT problem with a computational complexity upper bound of
the order Oe(m3(n + 1)m/ε2) where ε > 0 stands for the desired tolerance.

