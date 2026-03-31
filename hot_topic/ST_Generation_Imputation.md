# 🔍 ST_Generation_Imputation Papers · 2026-03-30

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Central-to-Local Adaptive Generative Diffusion Framework for Improving Gene Expression Prediction in Data-Limited Spatial Transcriptomics](https://arxiv.org/abs/2603.26827)**  `arXiv:2603.26827`  `cs.LG` `cs.AI` `cs.CV`  
  _Yaoyu Fang, Jiahe Qian, Xinkun Wang, Lee A. Cooper, Bo Zhou_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) provides spatially resolved gene expression profiles within intact tissue architecture, enabling molecular analysis in histological context. However, the high cost, limited throughput, and restricted data sharing of ST experiments result in severe data scarcity, constraining the development of robust computational models. To address this limitation, we present a Central-to-Local adaptive generative diffusion framework for ST (C2L-ST) that integrates large-scale morphological priors with limited molecular guidance. A global central model is first pretrained on extensive histopathology datasets to learn transferable morphological representations, and institution-specific local models are then adapted through lightweight gene-conditioned modulation using a small number of paired image-gene spots. This strategy enables the synthesis of realistic and molecularly consistent histology patches under data-limited conditions. The generated images exhibit high visual and structural fidelity, reproduce cellular composition, and show strong embedding overlap with real data across multiple organs, reflecting both realism and diversity. When incorporated into downstream training, synthetic image-gene pairs improve gene expression prediction accuracy and spatial coherence, achieving performance comparable to real data while requiring only a fraction of sampled spots. C2L-ST provides a scalable and data-efficient framework for molecular-level data augmentation, offering a domain-adaptive and generalizable approach for integrating histology and transcriptomics in spatial biology and related fields.
  </details>
