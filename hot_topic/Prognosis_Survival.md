# 🔍 Prognosis_Survival Papers · 2026-03-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Deep Learning From Routine Histology Improves Risk Stratification for Biochemical Recurrence in Prostate Cancer](https://arxiv.org/abs/2603.14187)**  `arXiv:2603.14187`  `cs.CV`  
  _Clément Grisi, Khrystyna Faryna, Nefise Uysal, Vittorio Agosti, Enrico Munari, Solène-Florence Kammerer-Jacquet, et al._
  <details open><summary>Abstract</summary>
  Accurate prediction of biochemical recurrence (BCR) after radical prostatectomy is critical for guiding adjuvant treatment and surveillance decisions in prostate cancer. However, existing clinicopathological risk models reduce complex morphology to relatively coarse descriptors, leaving substantial prognostic information embedded in routine histopathology underexplored. We present a deep learning-based biomarker that predicts continuous, patient-specific risk of BCR directly from H&E-stained whole-slide prostatectomy specimens. Trained end-to-end on time-to-event outcomes and evaluated across four independent international cohorts, our model demonstrates robust generalization across institutions and patient populations. When integrated with the CAPRA-S clinical risk score, the deep learning risk score consistently improved discrimination for BCR, increasing concordance indices from 0.725-0.772 to 0.749-0.788 across cohorts. To support clinical interpretability, outcome-grounded analyses revealed subtle histomorphological patterns associated with recurrence risk that are not captured by conventional clinicopathological risk scores. This multicohort study demonstrates that deep learning applied to routine prostate histopathology can deliver reproducible and clinically generalizable biomarkers that augment postoperative risk stratification, with potential to support personalized management of prostate cancer in real-world clinical settings.
  </details>

- **[Advancing Cancer Prognosis with Hierarchical Fusion of Genomic, Proteomic and Pathology Imaging Data from a Systems Biology Perspective](https://arxiv.org/abs/2603.13787)**  `arXiv:2603.13787`  `cs.CV`  
  _Junjie Zhou, Bao Xue, Meiling Wang, Wei Shao, Daoqiang Zhang_
  <details open><summary>Abstract</summary>
  To enhance the precision of cancer prognosis, recent research has increasingly focused on multimodal survival methods by integrating genomic data and histology images. However, current approaches overlook the fact that the proteome serves as an intermediate layer bridging genomic alterations and histopathological features while providing complementary biological information essential for survival prediction. This biological reality exposes another architectural limitation: existing integrative analysis studies fuse these heterogeneous data sources in a flat manner that fails to capture their inherent biological hierarchy. To address these limitations, we propose HFGPI, a hierarchical fusion framework that models the biological progression from genes to proteins to histology images from a systems biology perspective. Specifically, we introduce Molecular Tokenizer, a molecular encoding strategy that integrates identity embeddings with expression profiles to construct biologically informed representations for genes and proteins. We then develop Gene-Regulated Protein Fusion (GRPF), which employs graph-aware cross-attention with structure-preserving alignment to explicitly model gene-protein regulatory relationships and generate gene-regulated protein representations. Additionally, we propose Protein-Guided Hypergraph Learning (PGHL), which establishes associations between proteins and image patches, leveraging hypergraph convolution to capture higher-order protein-morphology relationships. The final features are progressively fused across hierarchical layers to achieve precise survival outcome prediction. Extensive experiments on five benchmark datasets demonstrate the superiority of HFGPI over state-of-the-art methods.
  </details>
