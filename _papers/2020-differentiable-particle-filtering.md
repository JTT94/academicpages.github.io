---
title: "Differentiable Particle Filtering"
collection: papers
permalink: /papers/2020-differentiable-particle-filtering
excerpt: 
date: 2020-04-01
venue: ICML 2021
paperurl: https://arxiv.org/abs/2102.07850
citation: @inproceedings{corenflos2021differentiable,
  title={Differentiable particle filtering via entropy-regularized optimal transport},
  author={Corenflos, Adrien and Thornton, James and Deligiannidis, George and Doucet, Arnaud},
  booktitle={International Conference on Machine Learning},
  pages={2100--2111},
  year={2021},
  organization={PMLR}
}
---

A novel, principled approach to Differentiable Particle Filtering, using Optimal Transport.

Paper: [https://arxiv.org/abs/2102.07850](https://arxiv.org/abs/2102.07850)

Particle Filtering (PF) methods are an established class of procedures for performing inference in non-linear state-space models. Resampling is a key ingredient of PF, necessary to obtain low variance likelihood and states estimates. However, traditional resampling methods result in PF-based loss functions being non-differentiable with respect to model and PF parameters. In a variational inference context, resampling also yields high variance gradient estimates of the PF-based evidence lower bound. By leveraging optimal transport ideas, we introduce a principled differentiable particle filter and provide convergence results. We demonstrate this novel method on a variety of applications.
Accepted as a Long talk at ICML 2021.

<img src="https://github.com/JTT94/jtt94.github.io/raw/de17f69ef86f61c7b739d59475d7c573c7d9af52/files/dm_maze.gif" width="800" height="300"/>


[Paper](https://arxiv.org/abs/2102.07850)


