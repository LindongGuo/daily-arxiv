# 🔍 ST_Generation_Imputation Papers · 2026-03-31

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Trimodal Deep Learning for Glioma Survival Prediction: A Feasibility Study Integrating Histopathology, Gene Expression, and MRI](https://arxiv.org/abs/2603.29968)**  `arXiv:2603.29968`  `cs.CV` `cs.AI`  
  _Iain Swift, JingHua Ye_
  <details open><summary>Abstract</summary>
  Multimodal deep learning has improved prognostic accuracy for brain tumours by integrating histopathology and genomic data, yet the contribution of volumetric MRI within unified survival frameworks remains unexplored. This pilot study extends a bimodal framework by incorporating Fluid Attenuated Inversion Recovery (FLAIR) MRI from BraTS2021 as a third modality. Using the TCGA-GBMLGG cohort (664 patients), we evaluate three unimodal models, nine bimodal configurations, and three trimodal configurations across early, late, and joint fusion strategies. In this small cohort setting, trimodal early fusion achieves an exploratory Composite Score (CS = 0.854), with a controlled $\Delta$CS of +0.011 over the bimodal baseline on identical patients, though this difference is not statistically significant (p = 0.250, permutation test). MRI achieves reasonable unimodal discrimination (CS = 0.755) but does not substantially improve bimodal pairs, while providing measurable uplift in the three-way combination. All MRI containing experiments are constrained to 19 test patients, yielding wide bootstrap confidence intervals (e.g. [0.400,1.000]) that preclude definitive conclusions. These findings provide preliminary evidence that a third imaging modality may add prognostic value even with limited sample sizes, and that additional modalities require sufficient multimodal context to contribute effectively.
  </details>

- **[LatentFM: A Latent Flow Matching Approach for Generative Medical Image Segmentation](https://arxiv.org/abs/2512.04821)**  `arXiv:2512.04821`  `cs.CV`  
  _Huynh Trinh Ngoc, Hoang Anh Nguyen Kim, Toan Nguyen Hai, Long Tran Quoc_
  <details open><summary>Abstract</summary>
  Generative models have achieved remarkable progress with the emergence of flow matching (FM). It has demonstrated strong generative capabilities and attracted significant attention as a simulation-free flow-based framework capable of learning exact data densities. Motivated by these advances, we propose LatentFM, a flow-based model operating in the latent space for medical image segmentation. To model the data distribution, we first design two variational autoencoders (VAEs) to encode both medical images and their corresponding masks into a lower-dimensional latent space. We then estimate a conditional velocity field that guides the flow based on the input image. By sampling multiple latent representations, our method synthesizes diverse segmentation outputs whose pixel-wise variance reliably captures the underlying data distribution, enabling both highly accurate and uncertainty-aware predictions. Furthermore, we generate confidence maps that quantify the model certainty, providing clinicians with richer information for deeper analysis. We conduct experiments on two datasets, ISIC-2018 and CVC-Clinic, and compare our method with several prior baselines, including both deterministic and generative approach models. Through comprehensive evaluations, both qualitative and quantitative results show that our approach achieves superior segmentation accuracy while remaining highly efficient in the latent space.
  </details>
