# 🔍 ST_Generation_Imputation Papers · 2026-03-17

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Segmentation-before-Staining Improves Structural Fidelity in Virtual IHC-to-Multiplex IF Translation](https://arxiv.org/abs/2603.16160)**  `arXiv:2603.16160`  `cs.CV`  
  _Junhyeok Lee, Han Jang, Heeseong Eum, Joon Jang, Kyu Sung Choi_
  <details open><summary>Abstract</summary>
  Multiplex immunofluorescence (mIF) enables simultaneous single-cell quantification of multiple biomarkers within intact tissue architecture, yet its high reagent cost, multi-round staining protocols, and need for specialized imaging platforms limit routine clinical adoption. Virtual staining can synthesize mIF channels from widely available brightfield immunohistochemistry (IHC), but current translators optimize pixel-level fidelity without explicitly constraining nuclear morphology. In pathology, this gap is clinically consequential: subtle distortions in nuclei count, shape, or spatial arrangement propagate directly to quantification endpoints such as the Ki67 proliferation index, where errors of a few percent can shift treatment-relevant risk categories. This work introduces a supervision-free, architecture-agnostic conditioning strategy that injects a continuous cell probability map from a pretrained nuclei segmentation foundation model as an explicit input prior, together with a variance-preserving regularization term that matches local intensity statistics to maintain cell-level heterogeneity in synthesized fluorescence channels. The soft prior retains gradient-level boundary information lost by binary thresholding, providing a richer conditioning signal without task-specific tuning. Controlled experiments across Pix2Pix with U-Net and ResNet generators, deterministic regression U-Net, and conditional diffusion on two independent datasets demonstrate consistent improvements in nuclei count fidelity and perceptual quality, as the sole modifications. Code will be made publicly available upon acceptance.
  </details>
