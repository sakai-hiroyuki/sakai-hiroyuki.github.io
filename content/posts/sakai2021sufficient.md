+++
title = "Sufficient Descent Riemannian Conjugate Gradient Methods"
date = "2024-01-23"
math = true
tags = ["査読付き原著論文"]
+++

# Sufficient Descent Riemannian Conjugate Gradient Methods
- Author: **Hiroyuki Sakai**, Hideaki Iiduka
- Journal: [Journal of Optimization Theory and Applications](https://link.springer.com/journal/10957) 190: 130-150 (2021)
- URL: https://link.springer.com/article/10.1007/s10957-021-01874-3
- GitHub: https://github.com/iiduka-researches/202104-sufficient

## Abstract
This paper considers sufficient descent Riemannian
conjugate gradient methods with line search algorithms.
We propose two kinds of sufficient descent nonlinear
conjugate gradient method and prove that
these methods satisfy the sufficient descent condition on Riemannian manifolds.
One is a hybrid method combining a Fletcher–Reeves-type
method with a Polak–Ribière–Polyak-type method,
and the other is a Hager–Zhang-type method, both of
which are generalizations of those used in Euclidean space.
Moreover, we prove that the hybrid method has a global
convergence property under the strong Wolfe conditions
and the Hager–Zhang-type method has the sufficient descent
property regardless of whether a line search is used or not.
Further, we review two kinds of line search algorithm
on Riemannian manifolds and numerically compare our
generalized methods by solving several Riemannian optimization problems.
The results show that the performance of the proposed hybrid methods greatly depends
on the type of line search used. Meanwhile, the Hager–Zhang-type method has the fast
convergence property regardless of the type of line search used.

## BibTeX
```bibtex
@article{sakai2021sufficient,
  title={Sufficient Descent {R}iemannian Conjugate Gradient Methods},
  author={Sakai, Hiroyuki and Iiduka, Hideaki},
  journal={Journal of Optimization Theory and Applications},
  volume={190},
  pages={130--150},
  year={2021},
  publisher={Springer}
}
```