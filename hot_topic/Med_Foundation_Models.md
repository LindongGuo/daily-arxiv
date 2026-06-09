# 🔍 Med_Foundation_Models Papers · 2026-06-08

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[SlideCheck: Guiding Self-Supervised Pretraining of Pathology Foundation Models via Dataset Distributions](https://arxiv.org/abs/2606.07590)**  `arXiv:2606.07590`  `cs.CV` `cs.AI`  
  _Mingyi He, Xinyi Guo, Xitong Ling, Weiming Chen, Jiawen Li, Lianghui Zhu, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models are pretrained on large streams of WSI-derived patches, while supervision during data construction is often slide-level, sparse, or heterogeneous. This mismatch makes it difficult to understand and control which biological patterns enter the pretraining data. We propose SlideCheck, a lightweight pretraining data guidance tool built on frozen pathology foundation model patch features. Rather than serving as a standalone patch diagnostic model, SlideCheck provides explicit abnormality and malignancy scores for organizing, filtering, and auditing pathology pretraining data. SlideCheck uses a dual-head MLP to separately model broad abnormal morphology and malignant evidence. A regularized feature-space scorer provides a supervised anchor for patch-level evidence estimation, while score-attention agreement combines patch scores with WSI-level MIL attention to mine high-confidence pseudo labels. The same scores are then used to construct broad-positive ViT pretraining subsets, where a patch is selected if either abnormality or malignancy evidence exceeds a threshold. Experiments show that SlideCheck-defined data distributions influence the downstream behavior of self-supervised ViT pretraining, indicating that biological composition is an important controllable factor in pathology foundation model development. Curated subsets can approach full-data performance, suggesting that explicitly scored patch pools may support more efficient and auditable pretraining data construction. These findings position SlideCheck as a data guidance and auditing layer for transforming large, undifferentiated patch pools into controllable and reusable pretraining datasets.
  </details>

- **[GD-MIL: Grade-Disentangled Multiple Instance Learning for Multimodal Biochemical Recurrence Prediction in Prostate Cancer](https://arxiv.org/abs/2606.09453)**  `arXiv:2606.09453`  `cs.CV`  
  _Dasari Naga Raju_
  <details open><summary>Abstract</summary>
  Biochemical recurrence (BCR) after radical prostatectomy is a critical endpoint in prostate cancer, yet risk stratification relies almost entirely on variables dominated by Gleason grade. Whether H&E whole slide images (WSIs) carry prognostic signal beyond grade, and whether multiple instance learning (MIL) can recover it, remains unsettled. A key obstacle is that many pipelines select model checkpoints on the evaluation fold, artificially inflating concordance. We construct a rigorous benchmark on TCGA-PRAD (487 patients, 101 BCR events) using strict out-of-fold scoring over five-fold cross-validation repeated across five seeds. The choice of MIL aggregator (ABMIL, CLAM, TransMIL, PatchGCN) has little effect (C-index 0.61-0.64 with UNI2-h), while the feature extractor is the dominant factor (ResNet50 0.566 versus pathology foundation models up to 0.639). A clinical Cox model on grade, stage, and age reaches 0.687; no imaging-only model significantly outperforms it (p > 0.10). We introduce Grade-Disentangled MIL (GD-MIL), a gated-attention MIL encoder trained with a gradient-reversal grade adversary that encourages the slide representation to be invariant to Gleason grade before late fusion with clinical variables. GD-MIL achieves C-index 0.704, significantly outperforming both the clinical baseline (delta-c = +0.029, p = 0.0005) and the best imaging-only model (delta-c = +0.062, p = 0.039), suggesting H&E morphology contains prognostic information complementary to grade. A median risk split yields log-rank p < 0.0001 separation in BCR-free survival (~20% vs ~70% at five years).
  </details>
