# 🔍 ST_Generation_Imputation Papers · 2026-04-21

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
  Flow matching has recently emerged as a principled framework for learning continuous-time transport maps, enabling efficient deterministic generation without relying on stochastic diffusion processes. While generative modeling has shown promise for medical image segmentation, particularly in capturing uncertainty and complex anatomical variability, existing approaches are predominantly built upon diffusion models, which incur substantial computational overhead due to iterative sampling and are often constrained by UNet-based parameterizations. In this work, we introduce MedFlowSeg, a conditional flow matching framework that formulates medical image segmentation as learning a time-dependent vector field that transports a simple prior distribution to the target segmentation distribution. This formulation enables one-step deterministic inference while preserving the expressiveness of generative modeling. We further develop a dual-conditioning mechanism to incorporate structured priors into the learned flow. Specifically, we propose a Dual-Branch Spatial Attention module that injects multi-scale structural information into the flow field, and a Frequency-Aware Attention module that models cross-domain interactions between spatial and spectral representations via discrepancy-aware fusion and time-dependent modulation. Together, these components provide an effective parameterization of conditional flows that capture both global anatomical structure and fine-grained boundary details. We provide extensive empirical validation across multiple medical imaging modalities, demonstrating that MedFlowSeg achieves state-of-the-art performance while significantly reducing computational cost compared to diffusion-based methods. Our results highlight the potential of flow matching as a theoretically grounded and computationally efficient alternative for generative medical image segmentation.
  </details>
