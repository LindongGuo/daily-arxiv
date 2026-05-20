# 🔍 ST_Generation_Imputation Papers · 2026-05-19

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[What Makes a Representation Good for Single-Cell Perturbation Prediction?](https://arxiv.org/abs/2605.19343)**  `arXiv:2605.19343`  `cs.LG`  
  _Wenkang Jiang, Yuhang Liu, Yichao Cai, Erdun Gao, Jiayi Dong, Ehsan Abbasnejad, et al._
  <details open><summary>Abstract</summary>
  Single-cell perturbation modeling is fundamental for understanding and predicting cellular responses to genetic perturbations. However, existing approaches, from causal representation learning to foundation models, often struggle with an overlooked challenge: gene expression is dominated by perturbation-invariant information, while perturbation-specific signals are intrinsically sparse. As a result, learned representations either entangle invariant and perturbation-specific information, leading to spurious and non-generalizable predictors, or suppress perturbation-specific signals altogether, rendering them ineffective for prediction. To address this, we propose PerturbedVAE, a general framework designed to resolve this signal imbalance. The framework explicitly separates perturbation-specific information from dominant invariant structure and recovers causal representations to effectively utilize such information for prediction. We further provide an identifiability analysis that characterizes the conditions under which sparse perturbation effects can be reliably recovered, thereby clarifying how the framework can be concretely specified under such conditions. Empirically, PerturbedVAE achieves state-of-the-art performance on a widely used benchmark across multiple evaluation settings, yielding significant gains on out-of-distribution combinatorial predictions and uncovering interpretable perturbation-response programs.
  </details>
