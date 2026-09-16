# 🔍 ST_Generation_Imputation Papers · 2026-09-15

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[MedPCFM-TED: One-Step Point Cloud Flow Matching for Implant Generation via Teacher-Guided Endpoint Distillation](https://arxiv.org/abs/2609.16934)**  `arXiv:2609.16934`  `cs.CV` `cs.LG`  
  _Kamil Kwarciak, Marek Wodzinski_
  <details open><summary>Abstract</summary>
  Cranial implant generation is an important task in medical imaging. Recent point cloud based generative methods, particularly flow matching, offer strong reconstruction quality and efficient sampling, but still require multiple neural function evaluations during inference. This limits rapid generation of multiple plausible implant candidates. We propose Teacher-guided Endpoint Distillation (TED), a simple one-step distillation framework for conditional cranial implant generation on point clouds. TED trains a one-step student using teacher-guided endpoint supervision and geometric matching losses, while avoiding explicit path straightening. We evaluate TED on the SkullFix and SkullBreak benchmarks. TED achieves the best overall performance on the SkullBreak dataset, remains competitive on SkullFix, and provides the strongest Chamfer distance performance among the compared one-step methods. In addition, TED generates implants in approximately 0.04s per sample. These results show that one-step distillation can substantially accelerate conditional point cloud implant generation without sacrificing reconstruction quality.
  </details>

- **[Hyperbolic Contrastive Learning with Entailment for Spatial Transcriptomics](https://arxiv.org/abs/2609.16207)**  `arXiv:2609.16207`  `cs.CV`  
  _Daniela Vega, Paula Cárdenas, Hannah Ceballos, Leonardo Manrique, Pablo Arbelaéz_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) has transformed biomedical research by enabling the spatial mapping of gene expression across tissue sections. However, high operational costs, specialized equipment requirements, and sensitivity to experimental noise limit the accessibility and scalability of ST. Recent computer vision approaches aim to overcome these limitations by predicting spatial gene expression directly from histopathology images. While effective, current approaches often suffer from gene expression over-smoothing and overly uniform predictions across tissue regions, suggesting that further progress depends on learning representations that reflect the hierarchical and asymmetric structure of gene regulation and tissue morphology. To address these issues, we propose Hyperbolic Contrastive Learning with Entailment for Spatial Transcriptomics (HyCLoST), a hyperbolic contrastive learning model that captures the intrinsic hierarchical relationships within ST data. By leveraging hyperbolic geometry and a gene-to-image entailment loss, HyCLoST learns structured, biologically grounded representations that improve gene expression prediction accuracy, achieving a 6% reduction in MSE and an 8% increase in PCC across 26 ST datasets, over previous methods. Our source code is publicly available atthis https URL
  </details>

- **[Semi-Supervised Learning-Based Genetic Biomarkers Dataset for Multiple-Stage Hepatocellular Carcinoma Prediction](https://arxiv.org/abs/2609.17100)**  `arXiv:2609.17100`  `cs.AI`  
  _Ahmed Ammar Kubba, Manar Abu Talib, Jibran Sualeh Muhammad, Ali Bou Nassif, Abdalla Sayed Mohamed, Darko Castven, et al._
  <details open><summary>Abstract</summary>
  Liver cancer is a complex disease responsible for a high number of deaths across the globe each year, making automated solutions for liver cancer classification urgent. The most common form of liver cancer is hepatocellular carcinoma (HCC), accounting for over 90% of liver cancer cases. There is a distinct lack of publicly available HCC datasets utilizing genomic data, which is necessary for training artificial intelligence (AI) models for automated HCC classification. This study proposes constructing a multi-stage HCC dataset using XGBoost and Semi-Supervised learning on three separate datasets of genomic biomarkers, utilizing their existing labels in the Semi-Supervised learning process to label the proposed dataset. The proposed dataset consists of 770 patient samples in total, categorized into five classes that represent normal tissue alongside different stages of HCC. Each sample in the dataset consists of 11,150 different gene expression levels. The XGBoost model demonstrated a final classification accuracy of 96.5% during the Semi-Supervised learning process.
  </details>
