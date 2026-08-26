# 🔍 ST_Generation_Imputation Papers · 2026-08-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Towards Reliable AI-Based Histological Staining: A Systematic Study of Scaling and Uncertainty in Unpaired Generative Models](https://arxiv.org/abs/2608.24626)**  `arXiv:2608.24626`  `cs.CV`  
  _Qasim Siddiqui, Adrian Friebel, Maiju Myllys, Zaynab Hobloss, Daniela Gonzalez, Ahmed Ghallab, et al._
  <details open><summary>Abstract</summary>
  Liver fibrosis, the principal predictor of long-term outcome in chronic liver disease, is staged from histological estimates of collagen content. Sirius Red (SR) provides the standard quantitative readout (collagen proportionate area, CPA) but is not acquired at every clinical centre and consumes tissue, time, and reagent cost beyond the routine Hematoxylin and eosin (H&E) stain. AI-based virtual staining can generate SR directly from H&E, yet systematic benchmarks of unsupervised models are scarce and their predictive uncertainty has not been quantified, even though visually plausible outputs may not faithfully reproduce the underlying tissue structure. We therefore benchmark six unsupervised image-to-image architectures (GAN-based and diffusion-based) across 54 scaling configurations on a newly released paired H&E to SR mouse liver dataset, the first open resource for this translation task. Each configuration is evaluated jointly on perceptual, distributional, and task-specific axes plus a blinded expert reader study; the best per family is then retrained as a deep ensemble, the first systematic comparison of epistemic uncertainty across unsupervised stain-to-stain architectures. Across families, perceptual quality, task-specific error, and ensemble agreement measure largely independent axes of model fitness: GAN-based methods cluster tightly on perceptual metrics yet differ substantially on task error and ensemble agreement, while the diffusion-based method (CycleDiffusion) is qualitatively different on all three. No single metric captures these differences, so reliable virtual staining requires reporting and selecting on all three jointly. The dataset, tiling pipeline, models, and evaluation code are released publicly.
  </details>
