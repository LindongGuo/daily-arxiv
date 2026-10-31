# 🔍 Multimodal_ST_Pathology Papers · 2026-10-30

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[STRATA: Reinforcement-driven Active Sampling with Tri-paradigm Adaptation for Efficient 3D Spatial Transcriptomics](https://arxiv.org/abs/2610.39151)**  `arXiv:2610.39151`  `cs.CV`  
  _Junchao Zhu, Ruining Deng, Chongyu Qu, Zhengyi Lu, Yanfan Zhu, Yuechen Yang, et al._
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables joint characterization of tissue morphology and gene expression. However, 3D volumetric ST acquisition remains expensive. AI-driven methods offer a low-cost alternative but remain limited in accuracy, while recent 2D section-wise ST acquisition still rely on dense grid sampling, resulting in redundant measurements and undersampling of biologically informative regions. To bridge the gap, we propose STRATA, a reinforcement-driven active sampling framework with tri-paradigm adaptation for reconstructing dense 3D transcriptomic maps from sparse voxel-wise ST acquisition. STRATA constructs a 3D graph integrating H&E morphology with single-cell priors and employs a reinforcement learning agent to estimate morphological sparsity and transcriptomic informativeness, enabling budget-aware selection of informative spots. Given these sparse measurements, an adaptive tri-paradigm predictor combines retrieval, regression, and cross-layer imputation through lightweight fusion, dynamically weighting their contributions. Experiments across datasets demonstrate improved sampling efficiency and accuracy, particularly under low-budget settings. Code is available atthis https URL.
  </details>
