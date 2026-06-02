# 🔍 Multimodal_ST_Pathology Papers · 2026-06-01

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[GC-MoE: Genomics-Guided Cell-Type-Specific Mixture of Experts for Histology-Based Single-Cell Spatial Transcriptomics](https://arxiv.org/abs/2606.02424)**  `arXiv:2606.02424`  `cs.CV` `cs.AI` `cs.LG`  
  _Kaito Shiku, Ahtisham Fazeel Abbasi, Ryoma Bise, Yuichiro Iwashita, Kazuya Nishimura, Andreas Dengel, et al._
  <details open><summary>Abstract</summary>
  Histology-based single-cell spatial transcriptomics (ST) estimation aims to predict gene expression for individual cells from histopathological images and cell locations, reducing the need for costly single-cell ST measurements. Unlike existing histology-to-ST methods that mainly predict spot-level profiles for local regions containing multiple cells, this task requires modeling cell-to-cell expression variability, which is strongly structured by cell type. We propose Genomics-Guided Cell-Type-Specific Mixture-of-Experts (GC-MoE), which estimates cell-type probabilities with a routing network and softly combines cell-type-specific experts for gene expression prediction. To further encode cell-type-dependent gene programs, we introduce the Cell-Type-Specific Co-Expression-Aware Predictor (CAP), together with a lightweight Cell-to-Cell Interaction Attention (C2CA) module for neighboring-cell context. Experiments and ablations on public single-cell ST datasets show consistent improvements over existing single-cell and adapted spot-level baselines.
  </details>
