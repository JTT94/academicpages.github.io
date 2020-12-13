---
title: "Differentiable Particle Filtering"
collection: papers
permalink: /papers/2020-differentiable-particle-filtering
excerpt: 
date: 2020-04-01
venue: 
paperurl: 
citation: 
---

Particle Filtering (PF) methods are a powerful class of procedures for performing state inference in state-space models and computing likelihood estimates for fixed parameters. Resampling is a key ingredient of PF, necessary to obtain low variance likelihood estimates. However, resampling operations result in the simulated likelihood function being non-differentiable with respect to parameters, even if the true likelihood is itself differentiable. Traditional resampling operations also yield high variance gradient estimates of the Evidence Lower Bound (ELBO) when performing variational inference. By leveraging Optimal Transport (OT) ideas, we introduce differentiable PF, providing a differentiable simulated likelihood function. This allows one to perform parameter estimation, including learning neural network parameterisations, via maximization of the simulated likelihood using gradient ascent, and also yields low variance gradient estimates for variational inference. We demonstrate the performance of differentiable PF on various examples.

Paper: Under review but available on request
