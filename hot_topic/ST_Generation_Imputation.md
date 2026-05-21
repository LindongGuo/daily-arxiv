# 🔍 ST_Generation_Imputation Papers · 2026-05-20

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Towards Autonomous Mechanistic Reasoning in Virtual Cells](https://arxiv.org/abs/2604.11661)**  `arXiv:2604.11661`  `cs.LG` `cs.AI`  
  _Yunhui Jang, Lu Zhu, Jake Fawkes, Alisandra Kaye Denton, Dominique Beaini, Emmanuel Noutahi_
  <details open><summary>Abstract</summary>
  Large language models (LLMs) have recently gained significant attention as a promising approach to accelerate scientific discovery. However, their application in open-ended scientific domains such as biology remains limited, primarily due to the lack of factually grounded and actionable explanations. To address this, we introduce a structured explanation formalism for virtual cells that represents biological reasoning as mechanistic action graphs, enabling systematic verification and falsification. Building upon this, we propose VCR-Agent, a multi-agent framework that integrates biologically grounded knowledge retrieval with a verifier-based filtering approach to generate and validate mechanistic reasoning autonomously. Using this framework, we release VC-TRACES dataset, which consists of verified mechanistic explanations derived from the Tahoe-100M atlas. Empirically, we demonstrate that training with these explanations improves factual precision and provides a more effective supervision signal for downstream gene expression prediction. These results underscore the importance of reliable mechanistic reasoning for virtual cells, achieved through the synergy of multi-agent and rigorous verification.
  </details>

- **[HAPS: Rethinking Image Similarity for Virtual Staining](https://arxiv.org/abs/2605.20362)**  `arXiv:2605.20362`  `cs.CV`  
  _Fedor Gubanov, Svetlana Illarionova, Vlad Kozlovskiy, Mikhail Romanov, Yersultan Akhmetov, Aida Akaeva, et al._
  <details open><summary>Abstract</summary>
  Virtual staining of histopathology images (e.g., H&E-IHC) is an emerging tool in digital pathology, enabling faster and cheaper workflows by synthesizing target stains from routinely acquired slides. Yet, the quality of virtual staining models is still predominantly assessed with generic metrics such as SSIM, PSNR, and LPIPS. Originally developed for natural images, these metrics are inherently misaligned with the domain-specific characteristics of histological data, failing to capture tissue morphology preservation and biomarker expression patterns. Consequently, a robust, domain-specific standard for quantifying similarity across diverse histological modalities remains a critical gap in the field. In this work, we formalize histology image similarity as a standalone problem and systematically evaluate a broad set of full-reference metrics against a dataset of H&E-IHC patch pairs annotated with expert similarity scores. We further analyze metrics sensitivity to controlled geometric distortions (shifts, rotations and non-rigid deformations) that mimic realistic registration errors between serial sections. Guided by these observations, we propose the Histology-Aware Perceptual Similarity (HAPS) metric. HAPS computes distances in the feature space of a frozen encoder pretrained on histopathology data, adding a linear head to aggregate feature-level differences into a final score that aligns with expert assessments. Finally, we demonstrate the practical value of HAPS for quality control of training data. By quantifying the similarity of training pairs in the MIST dataset and filtering low-scoring samples, we create a cleaner training set. Virtual staining models trained on this refined data outperform those trained on the original, unfiltered dataset.
  </details>
