# 🔍 Prognosis_Survival Papers · 2026-08-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[MultiSigBERT: Beyond Survival Analysis through Multimodal and Sequential Modeling in Oncology](https://arxiv.org/abs/2608.16972)**  `arXiv:2608.16972`  `cs.LG`  
  _Paul Minchella, Stéphane Chrétien, Guillaume Metzler, Loïc Verlingue, Rémi Vaucher_
  <details open><summary>Abstract</summary>
  Machine learning has become an essential component of modern healthcare, where the integration of heterogeneous data sources offers unprecedented opportunities to improve clinical decision-making. Electronic Health Records (EHR) contain complementary information -- including narrative clinical reports, numerical measurements, and structured variables -- yet most survival models remain limited to a single modality or fail to exploit the temporal nature of patient trajectories. We propose MultiSigBERT, a unified framework for multimodal sequential survival modeling in oncology based on path signature representations. Here, narrative medical reports (free-text) are converted into sentence embeddings by extracting and averaging contextual word embeddings. These representations are then compressed via modality-specific PCA and concatenated with structured covariates to form joint temporal trajectories which are then encoded using the Signature transform, a tool from Rough Paths theory that efficiently captures higher-order temporal interactions across modalities without supervision needed. The computed Signature features are finally incorporated as high dimensional features into a LASSO-regularized Cox model to estimate individualized risk scores. The performance of our novel MultiSigBERT pipeline is illustrated on the analysis of a real-world oncology cohort from the Léon Bérard Center, comprising over 120,000 medical reports and structured records from more than 2,500 patients. The model achieves a concordance index of 0.743 (sd 0.029) on an independent test set, demonstrating the benefit of jointly modeling multimodal temporal dynamics together with patient-level geometric structure for survival prediction.
  </details>

- **[Heterogeneity-Aware Deep Learning for Tumour Classification from Multiparametric MRI](https://arxiv.org/abs/2608.17254)**  `arXiv:2608.17254`  `cs.CV`  
  _Yue Xia, Euijoon Ahn, Tian Xia, Yuan Yuan, Michael Fulham, Jinman Kim_
  <details open><summary>Abstract</summary>
  Intra-tumoural heterogeneity (ITH) reflects spatial variation in tumour biology and is an important determinant of tumour behaviour, prognosis, and treatment response. Radiomics and deep learning have shown promise for tumour classification from multiparametric MRI (mp-MRI), but radiomics relies on handcrafted features, while most deep learning methods use whole-tumour representations or manually defined sub-regions, limiting scalable modelling of tumour heterogeneity. We propose a Heterogeneity-Aware Deep Learning Classification (HA-DLC) framework that explicitly models imaging-derived tumour sub-regions for lesion-type diagnosis and molecular-status prediction. HA-DLC consists of: (1) a Heterogeneous Sub-region Generation (HSG) module that produces initial pseudo-labelled sub-regions via unsupervised clustering, followed by Cross-Patient Sub-region Alignment (CPSA), which maps cluster-derived regions to a shared label space using soft assignments; and (2) a Dual-Stream Feature Extraction (DSFE) module that integrates local heterogeneity-aware features with global tumour representations. Given the initial clustering masks, CPSA, segmentation, feature extraction, and classification are jointly optimized end-to-end using soft-target segmentation and classification objectives. We evaluate HA-DLC on the LLD-MMRI2023 liver lesion dataset and the RSNA-ASNR-MICCAI 2021 Radiogenomic Brain Tumour dataset. HA-DLC consistently outperforms state-of-the-art radiomics and deep learning baselines, demonstrating the value of cross-patient sub-region alignment and dual-stream heterogeneity modelling for tumour classification from mp-MRI.
  </details>
