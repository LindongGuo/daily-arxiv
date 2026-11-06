# 🔍 Med_Foundation_Models Papers · 2026-11-05

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Scalable Bayesian Gaussian Process Classification for Cancer Histopathology: Calibrated Uncertainty Under Distribution Shift](https://arxiv.org/abs/2611.07127)**  `arXiv:2611.07127`  `cs.LG`  
  _Yunru Zheng, Wun Ting Chan, Sampras Dsouza, Zhenyu Hong_
  <details open><summary>Abstract</summary>
  Reliable uncertainty quantification is essential for clinical deployment of cancer diagnosis models, yet neural networks and variational Gaussian process methods can produce overconfident predictions, particularly under the distribution shifts that arise when models trained at one hospital are applied at another. We present a scalable Bayesian Gaussian Process Classification (GPC) framework that operates on frozen pathology foundation model embeddings (Phikon) and combines accelerated Randomly Pivoted Cholesky (RPCholesky) for low-rank kernel factorization, Hamiltonian Monte Carlo (HMC) with non-centered parameterization for posterior sampling, and a pivots-as-inducing-points scheme for prediction. This makes HMC posterior sampling in the low-rank latent representation tractable at N approximately 300,000 training points, enabling HC-based low-rank GPC on substantially larger datasets than prior MCMC-based demonstrations. We evaluate on two histopathology benchmarks for breast cancer metastasis detection: PCam and CAMELYON17-WILDS, where the latter tests calibration under hospital-level distribution shift. Compared to stochastic variational GP and neural network baselines, our method improves calibration and predictive performance - reducing expected calibration error by up to 88% and false negative rate by up to 90% - with the largest gains appearing under distribution shift, suggesting that HMC-based posterior sampling provides more trustworthy uncertainty estimates for cross-site pathology classification.
  </details>
