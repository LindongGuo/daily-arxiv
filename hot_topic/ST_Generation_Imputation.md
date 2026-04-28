# 🔍 ST_Generation_Imputation Papers · 2026-04-27

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Intervention-Aware Multiscale Representation Learning from Imaging Phenomics and Perturbation Transcriptomics](https://arxiv.org/abs/2604.22832)**  `arXiv:2604.22832`  `cs.CV` `cs.AI` `cs.LG`  
  _Jiayuan Chen, Ruoqi Liu, Zishan Gu, Ping Zhang_
  <details open><summary>Abstract</summary>
  Microscopy-based phenotypic profiling is scalable for drug discovery but lacks the mechanistic depth of transcriptomics, which remains costly and scarce. Existing multimodal approaches either use images to support other modalities or naively align representations by sample identity, ignoring cell-type and dose variations in weakly paired data-limiting generalization to unseen interventions. In this paper, we introduce an intervention-aware distillation framework that leverages perturbational transcriptomics to guide image representation learning. A transcriptome-conditioned teacher integrates gene expression and intervention metadata to produce soft distributions over a chemistry-aware codebook organized by drug similarity. The teacher employs a fine-tuned single-cell foundation model to encode cell-type context and disentangle dose effects. An image-only student learns to predict these distributions from microscopy alone, distilling mechanistic knowledge while operating independently at test time. This design emphasizes intervention semantics rather than identity alignment and explicitly handles dose and cell-type mismatches. We provide theoretical guarantees showing that transcriptomic guidance tightens the risk bound for image-based prediction. On Cell Painting and RxRx datasets paired with L1000, our method significantly improves one-shot transfer to unseen interventions and drug-target gene discovery compared to self-supervised and alignment baselines.
  </details>
