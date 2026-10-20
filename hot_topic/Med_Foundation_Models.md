# 🔍 Med_Foundation_Models Papers · 2026-10-19

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Multi-scale Fusion of Fast Vision Mamba and Foundation Model Features for Patch-Level Gleason Grading in Computational Pathology](https://arxiv.org/abs/2610.25904)**  `arXiv:2610.25904`  `cs.CV`  
  _Zihe Zhang, Weimiao Yu, Piumi Don Simonge_
  <details open><summary>Abstract</summary>
  Automated Gleason grading of prostate whole slide images (WSIs) enables faster and more consistent cancer risk stratification. However, it remains a challenging task due to the subtle morphological differences between grades, the severe class imbalance arising from rare patterns, and the diagnostic features that span multiple spatial scales. Pathology foundation models (FMs) extract strong patch representations but often operate at a single-scale, which limits spatial context and disproportionately affects classes that depend on broader context. The challenge of fusing multiple scales and complementary models, with minimal data and computational resources, remains unresolved. We propose a multi-scale classifier built on state-space models. Our method combines two complementary feature sources: a frozen foundation model, and a lightweight FastVim, pre-trained on ImageNet and distilled from the foundation model, that reads the raw image crops. At each scale, a Mamba model encodes the features from both sources with linear-time spatial context, and a jointly trained head fuses the encoded representations into one prediction. On the PANDA dataset, our method reaches macro F1 of 0.894 and Gleason 5 F1 of 0.802 under 5-fold cross-validation, a 12% and 21% relative improvement over the best single-scale model. A controlled study over 5 foundation models, 5 base classifiers and 3 scales confirms that the gain holds across encoders, with larger improvements observed at smaller scales.
  </details>

- **[MergeSurv: Merging-Based Continual Learning for Survival Analysis on Whole-Slide Images](https://arxiv.org/abs/2607.04747)**  `arXiv:2607.04747`  `cs.CV`  
  _Vu Minh Tran, Doanh C. Bui, Van-Hau Pham, Khang Nguyen_
  <details open><summary>Abstract</summary>
  Survival analysis on Whole Slide Images (WSIs) is important in computational pathology for prognosis estimation and treatment planning. However, existing survival models are typically trained independently for each cancer cohort, making continual adaptation computationally expensive for gigapixel-scale WSIs. In this study, we propose MergeSurv, a merging-based continual learning framework for WSI survival analysis. A pathology vision-language foundation model is independently fine-tuned on each task, and the learned parameters are sequentially merged into a unified model without storing previous training data. We further investigate two inference strategies: One-for-All (OFA) and Voting-Expert Aggregation (VEA). Experiments on four TCGA cohorts demonstrate that MergeSurv outperforms naive fine-tuning as well as representative regularization-based and rehearsal-based continual learning methods, while effectively reducing catastrophic forgetting. The results suggest that model merging is a promising direction for scalable and privacy-preserving continual learning in computational pathology.
  </details>
