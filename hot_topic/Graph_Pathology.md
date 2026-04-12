# 🔍 Graph_Pathology Papers · 2026-04-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Sampling-Aware 3D Spatial Analysis in Multiplexed Imaging](https://arxiv.org/abs/2604.07890)**  `arXiv:2604.07890`  `cs.CV`  
  _Ido Harlev, Tamar Oukhanov, Raz Ben-Uri, Leeat Keren, Shai Bagon_
  <details open><summary>Abstract</summary>
  Highly multiplexed microscopy enables rich spatial characterization of tissues at single-cell resolution, yet most analyses rely on two-dimensional sections despite inherently three-dimensional tissue organization. Acquiring dense volumetric data in spatial proteomics remains costly and technically challenging, leaving practitioners to choose between 2D sections or 3D serial sections under limited imaging budgets. In this work, we study how sampling geometry impacts the stability of commonly used spatial statistics, and we introduce a geometry-aware reconstruction module that enables sparse yet consistent 3D analysis from serial sections. Using controlled simulations, we show that planar sampling reliably recovers global cell-type abundance but exhibits high variance for local statistics such as cell clustering and cell-cell interactions, particularly for rare or spatially localized populations. We observe consistent behavior in real multiplexed datasets, where interaction metrics and neighborhood relationships fluctuate substantially across individual sections. To support sparse 3D analysis in practice, we present a reconstruction approach that links cell projections across adjacent sections using phenotype and proximity constraints and recovers single-cell 3D centroids using cell-type-specific shape priors. We further analyze the trade-off between section spacing, coverage, and redundancy, identifying acquisition regimes that maximize reconstruction utility under fixed imaging budgets. We validate the reconstruction module on a public imaging mass cytometry dataset with dense axial sampling and demonstrate its downstream utility on an in-house CODEX dataset by enabling structure-level 3D analyses that are unreliable in 2D. Together, our results provide diagnostic tools and practical guidance for deciding when 2D sampling suffices and when sparse 3D reconstruction is warranted.
  </details>
