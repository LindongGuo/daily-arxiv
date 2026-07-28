# 🔍 Multimodal_ST_Pathology Papers · 2026-07-27

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[HistoGPA: A Context-Conditioned Gene-Prior Attention Framework for Histology-Based Spatial Gene Expression Prediction](https://arxiv.org/abs/2607.24364)**  `arXiv:2607.24364`  `cs.CV`  
  _Ziang Liu, Xinhai Chen, Yigui Feng, Shuai Li, Qingyang Zhang, Jie Liu_
  <details open><summary>Abstract</summary>
  Predicting spatial gene expression from routine hematoxylin and eosin (H&E) images provides a practical complement to experimental spatial transcriptomics. Existing approaches focus on local or multi-scale visual features and often treat pretrained gene representations as fixed priors, although the interpretation of local morphology and the relevance of gene priors depend on tissue context. We propose HistoGPA, a context-conditioned gene-prior attention framework that uses a shared slide-level representation in two parallel pathways: one modulates local morphological features, whereas the other conditions pretrained gene embeddings and retrieves gene-prior information through cross-attention. This design enables each spatial location to retrieve context-adapted gene-prior information using its local morphology, position, and slide context. Across ten cancer types in HEST-1k, HistoGPA achieves the highest macro-averaged gene-wise Pearson correlation coefficient among the compared methods under the same evaluation protocol for both the top-50 and top-1,500 highly variable gene sets. Additional analyses show that HistoGPA better recovers the spatial expression patterns of cancer-associated genes and yields greater agreement between clusters derived independently from predicted and ground-truth expression profiles. Together, these findings motivate a context-dependent view of histology-to-expression prediction, in which local morphological representations and gene priors are jointly adapted to the broader tissue context.
  </details>
