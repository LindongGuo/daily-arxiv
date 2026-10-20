# 🔍 Graph_Pathology Papers · 2026-10-19

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[HGASurv: Hierarchical Granularity-Aware Integration for Multimodal Survival Prediction](https://arxiv.org/abs/2610.26357)**  `arXiv:2610.26357`  `cs.CV`  
  _Peike Yu, Wuchao Liu, Jihong Guan, Shuigeng Zhou_
  <details open><summary>Abstract</summary>
  Objective: Multimodal survival prediction jointly analyzes histopathological whole-slide images (WSIs), genomic profiles, and clinical variables to stratify patients by risk. However, existing approaches often inadequately account for granularity differences across modalities, particularly in spatial organization and feature dimensionality. To address these challenges, we propose HGASurv, which introduces a hierarchical WSI encoding module and a clinical-guided graph propagation module for granularity-aware multimodal integration. Methods: The hierarchical WSI encoding module maps WSI patch features onto a spatial grid using their original coordinates and applies parallel convolutions to construct representations at patch, local-neighborhood, and regional scales. Genomic signature embeddings then query these scale-specific WSI representations through cross-modal co-attention, producing signature-conditioned morphological features. The clinical-guided graph propagation module uses clinical variables to define patient-similarity edges and propagates fused image-genomic node embeddings with graph attention, integrating clinical information through topology rather than feature concatenation. Results: Across three TCGA cohorts, HGASurv achieved the strongest overall C-index performance, with ablation studies supporting the complementary contributions of the hierarchical WSI encoding and clinical-guided graph propagation modules. Conclusion and Significance: By introducing hierarchical WSI encoding and clinical-guided graph propagation, HGASurv unifies multi-scale pathology representation with topology-based clinical integration in a hierarchical granularity-aware framework. This design shows that matching representation and integration mechanisms to modality-specific granularity improves multimodal survival prediction.
  </details>
