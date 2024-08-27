+++
title = "Riemannian Adaptive Optimization Algorithm and Its Application to Natural Language Processing"
date = "2024-01-25"
tags = ["査読付き原著論文"]
+++

# Riemannian Adaptive Optimization Algorithm and Its Application to Natural Language Processing
- Author: **Hiroyuki Sakai**, Hideaki Iiduka
- Journal: [IEEE Transactions on Cybernetics](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6221036) 52 (8): 7328–7339 (2022)
- URL: https://ieeexplore.ieee.org/document/9339934

## Abstract
This article proposes a Riemannian adaptive optimization algorithm
to optimize the parameters of deep neural networks.
The algorithm is an extension of both AMSGrad in Euclidean space
and RAMSGrad on a Riemannian manifold.
The algorithm helps to resolve two issues affecting RAMSGrad.
The first is that it can solve the Riemannian stochastic optimization problem directly,
in contrast to RAMSGrad which only achieves a low regret.
The other is that it can use constant learning rates,
which makes it implementable in practice.
Additionally, we apply the proposed algorithm to Poincaré embeddings that embed the transitive
closure of the WordNet nouns into the Poincaré ball model of hyperbolic space.
Numerical experiments show that regardless of the initial value of the learning rate,
our algorithm stably converges to the optimal solution
and converges faster than the existing algorithms.

## BibTeX
```bibtex
@article{sakai2022riemannian,
  title={Riemannian Adaptive Optimization Algorithm and Its Application to Natural Language Processing},
  author={Sakai, Hiroyuki and Iiduka, Hideaki},
  journal={IEEE Transactions on Cybernetics},
  volume={52},
  number={8},
  pages={7328--7339},
  year={2022},
  publisher={IEEE}
}
```