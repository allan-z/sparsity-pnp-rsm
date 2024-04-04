# Fusing Sparsity with Deep Learning for Rotating Scatter Mask Gamma Imaging

Yilun Zhu, Clayton Scott, Darren Holland, George Landon, Aaron Fjeldsted, and Azaree Lintereur.
Fusing sparsity with deep learning for rotating scatter mask gamma imaging. In *IEEE Nuclear
Science Symposium and Medical Imaging Conference (NSS/MIC)*, 2022. 
[[arXiv]](https://arxiv.org/abs/2307.15884) 
[[IEEE]](https://ieeexplore.ieee.org/document/10399334)


**To do**
- [x] release the code that could reproduce experimental result
- [ ] provide a demo version



The repository contains code to reproduce the experiments in the paper.

What's more, we include implementations of several other methods:
- Maximum Likelihood Expectation Maximization (MLEM): a traditional method for image reconstruction in nuclear/medical imaging, that solves the Poisson likelihood optimization problem
  - and variants of it
- Alternating Direction Method of Multipliers (ADMM): a popular alternating optimization framework for solving various optimization problems, including
  - Lasso/$\ell_1$ regularization
  - Total Variation (TV) regularization
  - Plug-and-Play (PnP) priors
  - and combinations of them

with general version and accelerated version of that using FFT that is tailored for the specific problem of rotating scatter mask gamma imaging.
