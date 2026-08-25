# 🔍 ST_Generation_Imputation Papers · 2026-08-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[DeMixPert: Decomposed Response Modeling with Gaussian Mixtures for OOD Single-Cell Perturbation Prediction](https://arxiv.org/abs/2608.23114)**  `arXiv:2608.23114`  `cs.LG` `cs.AI`  
  _Jiawen Liu, Xuechenxiao Cao, Yutong Li, Bing Liu, Jiaming Liang, Tinghe Zhang, et al._
  <details open><summary>Abstract</summary>
  Predicting transcriptome-wide responses to unseen genetic perturbations remains a major computational challenge because accurate prediction requires recovering both perturbation-specific transcriptional shifts and heterogeneous cellular responses. Existing methods often entangle deterministic response structure with stochastic population-level variation, causing dominant shared patterns to mask weaker perturbation-specific signals and impair distributional modeling. To address these challenges, we propose \textbf{DeMixPert}, an approach for Decomposed response Modeling with Gaussian Mixtures for Out-Of-Distribution (OOD) single-cell Perturbation prediction. DeMixPert decomposes perturbation-induced changes into a basal-state-dependent systematic response, a perturbation-specific response, and population-level variation. The systematic component is derived from the basal state encoded from control-cell expression, whereas the perturbation-specific component is inferred from pretrained target embeddings for unseen-target generalization. DeMixPert models population-level variation using a Gaussian prototype Invertible Network and adaptively combines reusable Gaussian prototypes according to the basal state and perturbation condition. The resulting mixture is mapped to a condition-specific variation distribution. Sampled variations are integrated with the systematic and perturbation-specific components, followed by joint decoding with the basal state to reconstruct perturbed-cell gene expression. Experimental results show that DeMixPert effectively captures heterogeneous single-cell perturbation responses and achieves superior performance across unseen-perturbation settings. The source code is made publicly available upon publication.
  </details>

- **[SymmAdapt: Symmetrical Flow Matching for Source-Free Domain Adaptation in Medical Image Segmentation](https://arxiv.org/abs/2608.22532)**  `arXiv:2608.22532`  `cs.CV`  
  _Tal Grossman, Noa Cahan, Hayit Greenspan_
  <details open><summary>Abstract</summary>
  Domain shift across imaging modalities and acquisition sites remains a significant barrier to the clinical deployment of segmentation models. Source-free unsupervised domain adaptation (SFUDA) addresses this by adapting a pretrained model to an unlabeled target domain without requiring access to sensitive source data. We introduce a novel SFUDA framework built on Symmetrical Flow Matching, a unified generative model that segments an input image and synthesizes a source-like image from a mask within the same learned flow. By initializing inference from a domain-agnostic Gaussian origin, the model preserves structural consistency across domains and grounds predictions in learned anatomy rather than shifted texture statistics. Our pipeline leverages this symmetry to generate reliable pseudo-labels and corresponding source-like synthetic images from unlabeled target data, creating a generative replay buffer that anchors source knowledge during a generative self-training stage that fine-tunes on a joint set of real target and synthetic source-like images. We evaluate on abdominal multi-organ and cardiac segmentation, covering cross-modality MRI<->CT shifts, and multi-site prostate segmentation. Our approach outperforms SFUDA baselines and is competitive with conventional UDA methods.
  </details>
