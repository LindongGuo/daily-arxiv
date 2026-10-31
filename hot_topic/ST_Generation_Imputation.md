# 🔍 ST_Generation_Imputation Papers · 2026-10-30

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[STRATA: Reinforcement-driven Active Sampling with Tri-paradigm Adaptation for Efficient 3D Spatial Transcriptomics](https://arxiv.org/abs/2610.39151)**  `arXiv:2610.39151`  `cs.CV`  
  _Junchao Zhu, Ruining Deng, Chongyu Qu, Zhengyi Lu, Yanfan Zhu, Yuechen Yang, et al._
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables joint characterization of tissue morphology and gene expression. However, 3D volumetric ST acquisition remains expensive. AI-driven methods offer a low-cost alternative but remain limited in accuracy, while recent 2D section-wise ST acquisition still rely on dense grid sampling, resulting in redundant measurements and undersampling of biologically informative regions. To bridge the gap, we propose STRATA, a reinforcement-driven active sampling framework with tri-paradigm adaptation for reconstructing dense 3D transcriptomic maps from sparse voxel-wise ST acquisition. STRATA constructs a 3D graph integrating H&E morphology with single-cell priors and employs a reinforcement learning agent to estimate morphological sparsity and transcriptomic informativeness, enabling budget-aware selection of informative spots. Given these sparse measurements, an adaptive tri-paradigm predictor combines retrieval, regression, and cross-layer imputation through lightweight fusion, dynamically weighting their contributions. Experiments across datasets demonstrate improved sampling efficiency and accuracy, particularly under low-budget settings. Code is available atthis https URL.
  </details>

- **[SheafStain: Sheaf-Theoretic Schrödinger Bridge for Spatially and Biologically Coherent Virtual Staining](https://arxiv.org/abs/2606.11846)**  `arXiv:2606.11846`  `cs.CV`  
  _Hyeongyeol Lim, Hongjun Yoon, Eunjin Jang, Daeky Jeong, Won June Cho, Hwamin Lee_
  <details open><summary>Abstract</summary>
  Current virtual staining approaches offer the potential for time- and cost-efficient biomarker quantification in cancer diagnostics and prognostics. However, patch-wise inference for gigapixel whole-slide images fails to maintain spatial continuity, yielding artifacts that cause catastrophic mismatches with ground-truth images. Although pathology Vision Foundation Models (VFMs) offer rich representations, their self-attention causes varying global contexts to produce inconsistent embeddings for the same physical region. We formalize and validate this "context contamination" as a sheaf-theoretic problem where these embeddings form a presheaf whose sections disagree on overlaps, so no global section restricts to them. To address this, we propose SheafStain, a new approach that reinterprets VFM features as sheaf-like sections for spatially and biologically coherent virtual staining. Specifically, SheafStain integrates class and patch tokens into a Schrödinger Bridge framework as sheaf-like sections. While the class token anchors biological consistency, patch tokens form a per-position spatial map. A feature space from a single VFM encoder pretrained on Hematoxylin \& Eosin and Immunohistochemistry supervises both input conditioning and output stain alignment. Departing from prior work that evaluates on isolated $256 \times 256$ patches and either random-crops or resizes the $1024 \times 1024$ ground truth, we translate at $256 \times 256$ and evaluate on the stitched $1024 \times 1024$ outputs across HER2, ER, PR, and Ki-67. SheafStain demonstrates promising results against six prior methods while mitigating patch-boundary stitching artifacts. Code is available atthis https URL.
  </details>
