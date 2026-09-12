# 🔍 Multimodal_ST_Pathology Papers · 2026-09-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[DINO-Med: A Unified Patch-Based Adaptation Framework for Multi-Modal Medical Image Analysis Applied to Liver Fibrosis Staging](https://arxiv.org/abs/2609.11380)**  `arXiv:2609.11380`  `cs.CV`  
  _Boya Wang, Ruizhe Li, Chao Chen, Xin Chen_
  <details open><summary>Abstract</summary>
  Adapting natural-image foundation models like DINOv3 to multi-modal medical imaging is challenging due to the significant domain gap between natural color images and multi-channel medical scans. We present a unified, patch-based framework that processes raw multimodal imaging through training-free registration, automated localization, and mask-filtered patch extraction. This architecture culminates in a hierarchical strategy that aggregates patch-level insights into subject-level diagnostics. Using liver fibrosis staging as a case study, we evaluate four patch-level feature representations: handcrafted Radiomics features, learned ResNet features, pre-trained foundation model SAM-Med2D features, and frozen DINOv3 features. To ensure a controlled comparison, all models utilize the same lightweight MLP head and are evaluated across both rigid and deformable registration settings. Our training protocol focuses on mild fibrosis (S1) and cirrhosis (S4) classes only, enabling a single classifier to address both substantial fibrosis detection and cirrhosis staging. Evaluated via 10 random train (90%)/ test (10%) splits on 360 subjects from the CARE 2025 Liver Track 4 cohort, our DINOv3-based framework significantly outperforms all baselines, achieving the best classification accuracy of 78.4% for S1 and 75.8% for S4.
  </details>
