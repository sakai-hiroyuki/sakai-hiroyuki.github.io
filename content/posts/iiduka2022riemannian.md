+++
title = "Riemannian Stochastic Fixed Point Optimization Algorithm"
date = "2024-01-25"
math = true
tags = ["査読付き原著論文"]
+++

# Riemannian Stochastic Fixed Point Optimization Algorithm
- Author: Hideaki Iiduka, **Hiroyuki Sakai**
- Journal: [Numerical Algorithms](https://link.springer.com/journal/11075) 90: 1493–1517 (2022)
- URL: https://link.springer.com/article/10.1007/s11075-021-01238-y

## Abstract
This paper considers a stochastic optimization problem over the fixed point
sets of quasinonexpansive mappings on Riemannian manifolds.
The problem enables us to consider Riemannian hierarchical optimization problems
over complicated sets, such as the intersection of many closed convex sets,
the set of all minimizers of a nonsmooth convex function, and the intersection of
sublevel sets of nonsmooth convex functions. We focus on adaptive learning rate
optimization algorithms, which adapt step-sizes (referred to as learning rates in the machine
learning field) to find optimal solutions quickly. We then propose a Riemannian
stochastic fixed point optimization algorithm, which combines fixed point approximation
methods on Riemannian manifolds with the adaptive learning rate optimization algorithms.
We also give convergence analyses of the proposed algorithm for nonsmooth convex and smooth
nonconvex optimization. The analysis results indicate that, with small constant step-sizes,
the proposed algorithm approximates a solution to the problem. Consideration of the case
in which step-size sequences are diminishing demonstrates that the proposed algorithm
solves the problem with a guaranteed convergence rate. This paper also provides numerical
comparisons that demonstrate the effectiveness of the proposed algorithms with formulas
based on the adaptive learning rate optimization algorithms, such as Adam and AMSGrad.

## BibTeX
```bibtex
@article{iiduka2022riemannian,
  title={Riemannian stochastic fixed point optimization algorithm},
  author={Iiduka, Hideaki and Sakai, Hiroyuki},
  journal={Numerical Algorithms},
  volume={90},
  number={4},
  pages={1493--1517},
  year={2022},
  publisher={Springer}
}
```