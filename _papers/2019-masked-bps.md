---
title: "Masked Bouncy Particle Sampler"
collection: papers
permalink: /papers/2020-masked-bps
excerpt: 
date: 2019-01-01
venue: Preprint
paperurl: https://github.com/JTT94/jtt94.github.io/raw/master/files/Masked_Bouncy_Particle_Sampler.pdf
citation: 
code:
---

A parallelizble, continous time PDMP MCMC procedure.

<details>
  <summary>Cite</summary>
  
  ````
  @misc{thornton2020masked,
    title={The Masked Bouncy Particle Sampler: A Parallel, Chromatic, Piecewise-Deterministic Markov Chain Monte Carlo Method},
    author={Thornton, James},
    journal={https://jtt94.github.io/papers/2020-masked-bps},
    year={2020}
  }
````
</details>


Piecewise deterministic Markov Processes (PDMP) provide the foundation for a promising class of non-reversible, continuous-time Markov Chain Monte Carlo (MCMC) procedures and have been shown experimentally to enjoy attractive scaling properties in high-dimensional settings. This work introduces the Masked Bouncy Particle Sampler (BPS), a flexible MCMC procedure within the PDMP framework that exploits model structure and modern parallel computing resources using chromatic spatial partitioning ideas from the discrete-time MCMC literature (\cite{gonzalez2011parallel}). We extend the basic procedure by introducing a dynamic factorisation scheme of the target distribution to reduce boundary effects commonly associated to fixed partitioning. The validity of the proposed method is theoretically justified and we provide experimental evidence that the Masked Bouncy Particle Sampler delivers significant efficiency gains over other state-of-the-art sampling schemes for certain high-dimensional sparse models. 

[Paper](https://github.com/JTT94/jtt94.github.io/raw/master/files/Masked_Bouncy_Particle_Sampler.pdf)

