+++
title = "A general framework of Riemannian adaptive optimization methods with a convergence analysis"
date = "2025-04-07"
tags = ["査読付き原著論文"]
+++

# A general framework of Riemannian adaptive optimization methods with a convergence analysis
- Author: **Hiroyuki Sakai**, Hideaki Iiduka
- Journal: [Transactions on Machine Learning Research](https://jmlr.org/tmlr/) (2025)
- URL: https://openreview.net/forum?id=knv4lQFVoE

## Abstract
This paper proposes a general framework of Riemannian adaptive optimization methods. The framework encapsulates several stochastic optimization algorithms on Riemannian manifolds and incorporates the mini-batch strategy that is often used in deep learning. Within this framework, we also propose AMSGrad on embedded submanifolds of Euclidean space. Moreover, we give convergence analyses valid for both a constant and a diminishing step size. Our analyses also reveal the relationship between the convergence rate and mini-batch size. In numerical experiments, we applied the proposed algorithm to principal component analysis and the low-rank matrix completion problem, which can be considered to be Riemannian optimization problems. Python implementations of the methods used in the numerical experiments are available at https://github.com/iiduka-researches/202408-adaptive.

## BibTeX
```bibtex
@article{sakai2025general,
  title={A general framework of {R}iemannian adaptive optimization methods with a convergence analysis},
  author={Hiroyuki Sakai and Hideaki Iiduka},
  journal={Transactions on Machine Learning Research},
  issn={2835-8856},
  year={2025},
  url={https://openreview.net/forum?id=knv4lQFVoE},
  note={Reproducibility Certification}
}
```