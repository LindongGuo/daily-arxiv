# 🔍 Med_Foundation_Models Papers · 2026-04-10

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[T-Gated Adapter: A Lightweight Temporal Adapter for Vision-Language Medical Segmentation](https://arxiv.org/abs/2604.08167)**  `arXiv:2604.08167`  `cs.CV`  
  _Pranjal Khadka_
  <details open><summary>Abstract</summary>
  Medical image segmentation traditionally relies on fully supervised 3D architectures that demand a large amount of dense, voxel-level annotations from clinical experts which is a prohibitively expensive process. Vision Language Models (VLMs) offer a powerful alternative by leveraging broad visual semantic representations learned from billions of images. However, when applied independently to 2D slices of a 3D scan, these models often produce noisy and anatomically implausible segmentations that violate the inherent continuity of anatomical structures. We propose a temporal adapter that addresses this by injecting adjacent-slice context directly into the model's visual token representations. The adapter comprises a temporal transformer attending across a fixed context window at the token level, a spatial context block refining within-slice representations, and an adaptive gate balancing temporal and single-slice features. Training on 30 labeled volumes from the FLARE22 dataset, our method achieves a mean Dice of 0.704 across 13 abdominal organs with a gain of +0.206 over the baseline VLM trained with no temporal context. Zero-shot evaluation on BTCV and AMOS22 datasets yields consistent improvements of +0.210 and +0.230, with the average cross-domain performance drop reducing from 38.0% to 24.9%. Furthermore, in a cross-modality evaluation on AMOS22 MRI with neither model receiving any MRI supervision, our method achieves a mean Dice of 0.366, outperforming a fully supervised 3D baseline (DynUNet, 0.224) trained exclusively on CT, suggesting that CLIP's visual semantic representations generalize more gracefully across imaging modalities than convolutional features.
  </details>

- **[Plug-and-Play Logit Fusion for Heterogeneous Pathology Foundation Models](https://arxiv.org/abs/2604.07779)**  `arXiv:2604.07779`  `cs.CV`  
  _Gexin Huang, Anqi Li, Yusheng Tan, Beidi Zhao, Gang Wang, Gaozu Hua, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) have become central to computational histopathology, offering strong transfer performance across a wide range of diagnostic and prognostic tasks. The rapid proliferation of pathology foundation models creates a model-selection bottleneck: no single model is uniformly best, yet exhaustively adapting and validating many candidates for each downstream endpoint is prohibitively expensive. We address this challenge with a lightweight and novel model fusion strategy, LogitProd, which treats independently trained FM-based predictors as fixed experts and learns sample-adaptive fusion weights over their slide-level outputs. The fusion operates purely on logits, requiring no encoder retraining and no feature-space alignment across heterogeneous backbones. We further provide a theoretical analysis showing that the optimal weighted product fusion is guaranteed to perform at least as well as the best individual expert under the training objective. We systematically evaluate LogitProd on \textbf{22} benchmarks spanning WSI-level classification, tile-level classification, gene mutation prediction, and discrete-time survival modeling. LogitProd ranks first on 20/22 tasks and improves the average performance across all tasks by ~3% over the strongest single expert. LogitProd enables practitioners to upgrade heterogeneous FM-based pipelines in a plug-and-play manner, achieving multi-expert gains with $\sim$12$\times$ lower training cost than feature-fusion alternatives.
  </details>
