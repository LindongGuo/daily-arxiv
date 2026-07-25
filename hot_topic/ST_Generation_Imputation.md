# 🔍 ST_Generation_Imputation Papers · 2026-07-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[DS@GT ARC at ImageCLEFmed GANs 2026: Geometric Filtering for Privacy-Preserving CT Slice Generation](https://arxiv.org/abs/2607.20692)**  `arXiv:2607.20692`  `cs.CV` `cs.AI`  
  _Eric Regina, Richard Arnaud, Samir Hadi Cisneros_
  <details open><summary>Abstract</summary>
  We present a privacy-preserving framework for synthetic lung CT slice generation developed for the Image-CLEFmed GANs 2026 challenge. The approach combines Optimal Transport Conditional Flow Matching with privacy-oriented training and a post-generation "Supervisor" pipeline that filters generated candidates in learned geometric latent spaces using autoencoder embeddings, Determinantal Point Processes, and Stein Kernel Thinning. Official results show a strong realism-privacy trade-off, with the best-performing model achieving a Privacy Preservation Score of 0.549 and competitive visual fidelity with an FID of 0.3290. While the proposed geometric filtering substantially reduces nearest-neighbor memorization and membership-inference leakage, persistent patient re-identification scores indicate that preventing direct image copying is not sufficient to remove deeper patient-specific anatomical identity, highlighting an important frontier for future privacy-preserving medical image generation.
  </details>

- **[Physics-Informed Deep Learning Model for Cross-Modality Super-Resolution in Fluorescence Microscopy](https://arxiv.org/abs/2607.21190)**  `arXiv:2607.21190`  `cs.CV`  
  _Mohammad Soltaninezhad, Elena Corbetta, Francisco Paez Larios, Paul M. Jordan, Oliver Werz, Christian Eggeling, et al._
  <details open><summary>Abstract</summary>
  Cross-modality image translation offers a route to super-resolution fluorescence microscopy from low-resolution images while reducing phototoxicity and instrumentation demands. However, purely data-driven models can produce visually plausible outputs that are inconsistent with optical image formation. Here, we propose a physics-informed generative adversarial network for confocal-to-STED image translation that incorporates microscope-specific point spread function information into the training objective. Simulated and experimentally measured PSFs were evaluated using a limited paired confocal-STED dataset of TOM20-labeled mitochondria in human primary M2 macrophages acquired across different experimental days. Performance was assessed using reference-based and non-reference-based image-quality metrics, together with complementary frequency- and distribution-sensitive analyses. The no-reference metrics probed physics-relevant image properties, including spatial-frequency content, contrast, and signal-to-noise behavior. PSF-guided models improved structural fidelity, reduced local deviations, and achieved closer agreement with STED references than non-PSF baselines, particularly in frequency-domain analyses. These results demonstrate that optical priors can improve the structural fidelity and physical plausibility of generative microscopy models for cross-modality super-resolution imaging.
  </details>
