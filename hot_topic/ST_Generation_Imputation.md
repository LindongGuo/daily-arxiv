# 🔍 ST_Generation_Imputation Papers · 2026-05-08

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[MedFlowSeg: Flow Matching for Medical Image Segmentation with Frequency-Aware Attention](https://arxiv.org/abs/2604.19675)**  `arXiv:2604.19675`  `cs.CV`  
  _Zhi Chen, Runze Hu, Le Zhang_
  <details open><summary>Abstract</summary>
  Flow matching has recently emerged as a principled framework for learning continuous-time transport maps, enabling efficient ODE-based sampling without relying on stochastic diffusion processes. While generative modeling has shown promise for medical image segmentation, particularly in capturing uncertainty and complex anatomical variability, existing approaches are predominantly based on diffusion models, which require iterative sampling and incur substantial computational overhead. In this work, we propose MedFlowSeg, a conditional flow matching framework that formulates medical image segmentation as learning a time-dependent vector field that transports a simple prior distribution to the target segmentation distribution. Compared to diffusion-based methods, our formulation enables more efficient inference through solving an ordinary differential equation, while preserving the flexibility of generative modeling. To effectively incorporate conditional information, we introduce a dual-conditioning mechanism. Specifically, we propose a Dual-Branch Spatial Attention (DB-SA) module to inject multi-frequency structural priors, and a Frequency-Aware Attention (FA-Attention) module to model interactions between spatial and spectral representations via discrepancy-aware fusion and time-dependent modulation. These components improve the alignment between noisy intermediate states and clean semantic features, leading to better structural consistency and boundary delineation. We conduct extensive experiments across multiple medical imaging modalities, where MedFlowSeg consistently outperforms prior state-of-the-art (SOTA) baselines, including diffusion-based and flow-based methods.
  </details>
