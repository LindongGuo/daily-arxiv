# 🔍 Graph_Pathology Papers · 2026-09-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Conserved Immune Topology Improves Pathology Foundation Model Generalization for Cross-Cancer MSI-H Prediction](https://arxiv.org/abs/2609.05182)**  `arXiv:2609.05182`  `cs.CV`  
  _Dasari Naga Raju_
  <details open><summary>Abstract</summary>
  Pathology foundation models integrated with multiple instance learning achieve competitive accuracy within single-cancer cohorts, yet cross-cancer generalization remains unresolved due to organ-specific histological and architectural differences. In this paper, we propose Conserved Immune Topology (CIT), a lightweight spatial representation for cross-cancer MSI-H prediction that augments foundation-model embeddings with biologically motivated immune descriptors. CIT uses unsupervised clustering to identify immune-associated tiles, then encodes tertiary lymphoid structures, peritumoral immune reactions, multi-scale tumor-infiltrating lymphocyte density, and immune-tumor mixing from frozen foundation-model embeddings and tile coordinates without requiring annotations or target-domain data. The proposed method was evaluated under cross-site and cross-cancer settings using CPTAC-COAD and TCGA-STAD cohorts, which introduce scanner variability, distribution shifts, and organ-specific architectural variations. Zero-shot cross-cancer transfer with CIT increased TransMIL AUC from 0.6627 to 0.7161, an absolute gain of 0.0534 (p=0.003), with consistent improvements across all three MIL aggregators. These results suggest that spatial immune topology provides potentially an organ-invariant representation for MSI-H prediction, supporting cross-cancer generalization of pathology foundation models.
  </details>
