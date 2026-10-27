# 🔍 Multimodal_ST_Pathology Papers · 2026-10-26

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Biology-Guided Context-Aware Residual Propagation for Spatial Gene Expression Prediction from Histology](https://arxiv.org/abs/2610.35167)**  `arXiv:2610.35167`  `cs.LG`  
  _Vu Van An, Long D. Nguyen, Ho Viet Duc Luong, Binh P. Nguyen_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics provides spatially resolved molecular profiling, but its cost, limited throughput and experimental complexity hinder routine large-scale use. Predicting spatial gene expression from hematoxylin-and-eosin-stained histology images offers a scalable alternative, yet remains challenging because histology provides only an indirect morphological view of molecular activity. Existing methods typically decode expression from visual features in a single stage, even when enhanced with spatial aggregation, retrieval or multi-resolution fusion. This formulation is restrictive because spot-level expression reflects not only local morphology but also cellular identity, neighborhood composition and tissue-level organization. We propose BCARP, a Biology-guided Context-Aware Residual Propagation framework for histology-guided spatial transcriptomics prediction. Instead of directly predicting gene expression from histology embeddings, BCARP treats them as morphology visual priors and progressively refines spot representations in a transcriptomics-oriented latent space. Each refinement step integrates nuclei-guided local cellular context with prototype-guided global context propagation, enabling information exchange across both neighboring and spatially distant spots. A pattern-scale decoder further separates spatial expression into pattern prediction from raw expression with scale calibration. Evaluated on three ST datasets and ten HEST-1k cohorts, BCARP achieves the highest mean correlation-based performance against other baselines. Numerical results support biology-guided local-global residual propagation as an effective alternative to visual decoding for histology-to-transcriptomics prediction.
  </details>
