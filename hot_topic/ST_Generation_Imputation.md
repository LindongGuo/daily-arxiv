# 🔍 ST_Generation_Imputation Papers · 2026-04-06

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Uncertainty Quantification for Distribution-to-Distribution Flow Matching in Scientific Imaging](https://arxiv.org/abs/2603.21717)**  `arXiv:2603.21717`  `cs.LG`  
  _Dongxia Wu, Yuhui Zhang, Serena Yeung-Levy, Emma Lundberg, Emily B. Fox_
  <details open><summary>Abstract</summary>
  Distribution-to-distribution generative models support scientific imaging tasks ranging from modeling cellular perturbation responses to translating medical images across conditions. Trustworthy generation requires both reliability (generalization across labs, devices, and experimental conditions) and accountability (detecting out-of-distribution cases where predictions may be unreliable). Uncertainty quantification (UQ) based approaches serve as promising candidates for these tasks, yet UQ for distribution-to-distribution generative models remains underexplored. We present a unified UQ framework, Bayesian Stochastic Flow Matching (BSFM), that disentangles aleatoric and epistemic uncertainty. The Stochastic Flow Matching (SFM) component augments deterministic flows with a diffusion term to improve model generalization to unseen scenarios. For UQ, we develop a scalable Bayesian approach -- MCD-Antithetic -- that combines Monte Carlo Dropout with sample-efficient antithetic sampling to produce effective anomaly scores for out-of-distribution detection. Experiments on cellular imaging (BBBC021, JUMP) and brain fMRI (Theory of Mind) across diverse scenarios show that SFM improves reliability while MCD-Antithetic enhances accountability.
  </details>
