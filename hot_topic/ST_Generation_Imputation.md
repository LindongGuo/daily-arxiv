# 🔍 ST_Generation_Imputation Papers · 2026-06-22

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Contrastive and Adaptive Multi-modal Masked Autoencoder for Spatial Transcriptomics](https://arxiv.org/abs/2606.21156)**  `arXiv:2606.21156`  `cs.CV` `cs.AI`  
  _Joohyeok Kim, Taejin Jeong, Jinyeong Kim, Seong Jae Hwang_
  <details open><summary>Abstract</summary>
  The high cost of spatial transcriptomics (ST) has driven extensive studies into predicting gene expression directly from H&E histology images. However, this prediction task faces an inherent limitation, as tissue morphology alone provides insufficient information to fully resolve underlying gene expression. To address this limitation, a recent study leverages partial gene expression to guide the prediction process alongside histology images. Building on this paradigm, we approach the prediction task as a spatial imputation problem, employing a Masked Autoencoder (MAE) to utilize a small fraction of gene expression as genetic anchors for inferring whole-slide gene expression profiles. Specifically, we propose a bio-saliency score and a learning-to-rank strategy to adaptively identify the most informative spots within the tissue. Based on these identified spots, our framework selects contiguous regions as genetic anchors to ensure suitability for real-world ST profiling hardware. To effectively leverage these anchors, we design a cross-modal joint encoder that integrates visual and genetic modalities. By aligning the selected anchors with their corresponding visual features via contrastive learning, the encoder generates robust joint representations to accurately predict gene expression across the whole slide. Notably, our framework consistently surpasses existing methods in both histology-only prediction and spatial imputation, achieving superior accuracy even without genetic anchors and further excelling with as little as 10% transcriptomic coverage. Our code is available atthis https URL.
  </details>
