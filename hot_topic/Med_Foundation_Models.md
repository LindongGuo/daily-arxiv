# 🔍 Med_Foundation_Models Papers · 2026-09-21

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[DiaSeg: Diagonal Segment Extraction from DTW Paths for Interpretable Gait Analysis](https://arxiv.org/abs/2609.24223)**  `arXiv:2609.24223`  `cs.CV`  
  _Tresor Y. Koffi, Amel Hidouri, Corentin Legrand, Aurélie Bertaux_
  <details open><summary>Abstract</summary>
  Dynamic Time Warping (DTW) is the dominant approach for measuring similarity between time series, yet standard practice discards the optimal warping path after computing a single distance value, losing local alignment information most relevant to clinical diagnosis. We introduce DiaSeg, a framework that extracts diagonal segments from DTW paths with controlled breaks, characterizing each segment by five geometric features (effective length, interruption count, cost variation, temporal position, and path context), and enabling unsupervised pattern discovery without domain-specific feature engineering. Validated on 91 subjects across six clinical conditions (healthy aging, Parkinson's, Huntington's, ALS, brain tumor, and stroke), three findings emerge. First, diagonal segments form consistent unsupervised patterns (silhouette 0.33) aligned with biomechanical phase annotations, with label-based validation confirming near-perfect separation of healthy and pathological gait (ARI up to 0.986). Second, segments discriminate pathology at 69% (supervised) and 75% (patient-level clustering), with pathology manifesting through distributional shifts in segment length; combining segment and cycle-level features further improves classification to 91.7%. Third, while cycle-based methods achieve higher accuracy (91%), diagonal segments provide phase-specific interpretability unavailable in global representations, localizing where coordination breaks down within the gait cycle. DiaSeg thus transforms DTW from a black-box distance into a source of interpretable temporal features for neurodegenerative disease assessment.
  </details>

- **[Patch-to-Global: Random Patch Diffusion for Globally Consistent Megapixel Artifact Inpainting in Whole Slide Images](https://arxiv.org/abs/2609.24116)**  `arXiv:2609.24116`  `cs.CV`  
  _Hyeseong Lee, Eunsu Kim, D M Bappy, Ho Heon Kim, Youngsuk Lee, Se Young Chun, et al._
  <details open><summary>Abstract</summary>
  Although deep learning has advanced Whole Slide Image (WSI) Analysis, tissue artifacts like bubbles and folds often cause silent failures by concealing essential morphology. Current pathology image restoration methods are mostly restricted to small patches, struggling to maintain global structural coherence at a megapixel scale. We introduce RestorePath, a framework for globally consistent megapixel scale inpainting that reconstructs diagnostic structures in histological image to prevent incorrect high-confidence predictions and lower error rates. Our model utilizes a Latent Diffusion Model (LDM) conditioned on Pathology Foundation Model (PFM) embeddings, integrating Large Kernel Attention (LKA) to manage long-range dependencies during random patch diffusion. Enhanced by Distance-Weighted Interpolation (DWI) and an Adaptive Guidance Scale (AGS), RestorePath ensures structural consistency and fidelity by modulating information from surrounding patches. Evaluations across TCGA-BRCA, BACH, and Camelyon16 datasets for images ranging from 512 to 4608 pixels demonstrate state-of-the-art performance in maintaining histological consistency. RestorePath significantly improves downstream Computational Pathology (CP) tasks, outperforming both raw artifact images and the conventional Detect-and-Discard (D&D) approach. The code is available atthis https URL
  </details>
