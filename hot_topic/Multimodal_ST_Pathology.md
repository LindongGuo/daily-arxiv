# 🔍 Multimodal_ST_Pathology Papers · 2026-11-09

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[CXR-CMFA: A Cross-Modal Feature Aggregation Network for Chest X-Ray Pathology Classification](https://arxiv.org/abs/2611.10174)**  `arXiv:2611.10174`  `cs.CV` `cs.AI`  
  _Talukder Hasnat Zadid, Jahin Sultana, Felipe Bochini Brisola, Kishore Roy, Mysha Rahman, Syeda Asrafa Islam, et al._
  <details open><summary>Abstract</summary>
  Chest X-ray (CXR) interpretation remains challenging because subtle pathology can be obscured by overlapping anatomy, image-quality variation, and limited visual evidence in isolated radiographs. Although image-only deep learning models provide useful baselines, they discard the complementary diagnostic context available in radiology reports, while large vision-language models can be computationally expensive for practical deployment. This paper presents CXR-CMFA, a lightweight cross-modal feature aggregation network for binary CXR pathology classification. The proposed framework combines a dual-stream visual encoder, using EfficientNet-B0 for global anatomical representation and DenseNet-121 for local pathological detail, with a TF-IDF-MLP report encoder. Two fusion modules integrate these modalities: the Dual-Modal Spatial Attention Module (DMSAM) uses the report embedding to gate global and local visual features, and the Cross-Modal Gated Feature Fusion (CGFF) module learns per-instance weights for visual and textual contributions. Experiments on the MIMIC-CXR benchmark, using the provided train, validation, and test splits, show that CXR-CMFA achieves 93.45% accuracy, 99.88% precision, 91.8% recall, 95.7% F1-score, and 99.19% AUC on the held-out test set. The model produces only four false positives among 984 normal test cases, supporting its suitability for high-specificity screening workflows. An ablation study further demonstrates a 22.47 percentage-point AUC improvement over the global-image-only variant, confirming the value of adaptive cross-modal fusion. These results indicate that compact report-conditioned fusion can provide strong discriminative performance without relying on large pretrained language models.
  </details>
