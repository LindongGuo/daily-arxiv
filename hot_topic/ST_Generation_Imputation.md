# 🔍 ST_Generation_Imputation Papers · 2026-10-20

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[HistoLoop: Iterative Contextual Inference with a Looped Transformer for Histology-Based Spatial Gene Expression Prediction](https://arxiv.org/abs/2610.28339)**  `arXiv:2610.28339`  `cs.CV`  
  _Ziang Liu, Jie Liu, Shuai Li, Yigui Feng, Qinglin Wang_
  <details open><summary>Abstract</summary>
  Predicting spatial gene expression from H&E images offers a scalable complement to experimental spatial transcriptomics. However, despite progress in spatial context modeling, how to construct subsequent context from spot states updated by earlier contextual interactions remains underexplored. We introduce HistoLoop, a looped Transformer that formulates prediction as iterative contextual inference. At each refinement step, HistoLoop aggregates the current spot states into context tokens at the corresponding resolution, processes them with a shared spatial Transformer, and retrieves spot-specific contextual information through cross-attention. A memory-mediated update integrates this information into persistent spot states, which are then used to construct context at the next, finer resolution. Under the HEST-Bench HVG50 evaluation protocol, HistoLoop achieves the highest macro-averaged gene-wise Pearson correlation among the compared methods across six cancer-specific tasks spanning five organs in HEST-1K. Ablation studies support the importance of recurrent state refinement and reconstructing context from updated spot states at progressively finer resolutions. Expression-derived clustering further suggests that HistoLoop better captures spatially organized multigene patterns.
  </details>

- **[REST: Reliability-Guided Spatial Transcriptomics Supervision for Gene Expression Prediction from Histopathological HE-Stained Images](https://arxiv.org/abs/2610.26988)**  `arXiv:2610.26988`  `cs.CV`  
  _Lanfeng Zhong, Xiangyu Sun, Guixuan Xu, Rongzhao Zhang, Jie Xu, Shaoting Zhang, et al._
  <details open><summary>Abstract</summary>
  Histopathology is central to cancer diagnosis, but morphology in Hematoxylin and Eosin (HE)-stained images does not directly reveal the molecular states that characterize disease heterogeneity and inform tumor characterization, prognostic assessment, and biomarker discovery. Spatial Transcriptomics (ST) measures spatially resolved gene expression, providing molecular information within tissue architecture, yet differences in assay coverage and spot informativeness make paired HE--ST observations unequally reliable for representation learning. We propose Reliability-Guided Spatial Transcriptomics (REST) supervision with Biological Program Bank (BPB), a program-structured and reliability-guided ST-supervised training framework for predicting molecular information from H\&E images. REST constructs BPB from curated signature, pathway, and cell-type gene sets to provide a shared structure for ST encoding, reliability estimation, and molecular reconstruction. Guided by BPB, Spot-Reliability Contrastive Alignment (SRCA) measures the reliability of each spot from assay-level program coverage and spot-level activity dispersion, and reweights HE--ST alignment accordingly. Biology-Informed Program Reconstruction (BIPR) further uses learnable program queries to reconstruct member-gene expression from histological morphology. REST's training corpus comprised 209 samples (407,475 spots across 16 organs); evaluation used 70 disjoint samples (230,056 spots across eight organs) for gene-expression, pathway-activity, and cell-signature prediction. REST achieved the highest Macro correlation among state-of-the-art ST-supervised training methods and outperformed existing pathology foundation models. Code is available atthis https URL.
  </details>
