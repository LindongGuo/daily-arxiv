# 🔍 Multimodal_ST_Pathology Papers · 2026-10-17

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[When to Align, When to Predict: A Phase Diagram for Multimodal Learning](https://arxiv.org/abs/2606.11190)**  `arXiv:2606.11190`  `cs.LG`  
  _Ilay Kamai, Hugues Van Assel, Aviv Regev, Hagai B. Perets, Randall Balestriero_
  <details open><summary>Abstract</summary>
  Cross-modal alignment (CA) and cross-modal prediction (CP) are the dominant paradigms for multimodal representation learning, yet there is no systematic understanding of when each succeeds and when each fails, a gap that leaves practitioners, especially in scientific domains with heterogeneous instruments and multiple levels of measurement, unable to diagnose why standard methods underperform the best single modality. We study both objectives under a spiked signal-plus-noise model with structured cross-modal nuisance correlation, the ingredient that breaks the classical recovery guarantees, and derive separation ratios that expose complementary failure modes: alignment whitens each modality and fails when nuisance is strongly correlated across views; prediction encodes whatever is cross-predictable through a one-sided whitening, with recovery governed by source-modality quality. The resulting phase diagram partitions multimodal problems into four regimes --- Both, CA only, CP only, and Neither --- refined by a recovery count that separates partial recovery from complete failure. We present a data-driven procedure to locate real-world datasets in this diagram using a small labeled subsample, identifying the preferred objective and prediction direction before any cross-modal training, and identifying when no objective in the CA/CP family can improve on the stronger modality alone. Experiments on synthetic data, stereo-vision benchmarks, image--caption pairs, and two real scientific domains, astronomy and single-cell multi-omics, validate the predictions in the nonlinear regime, including both faces of the Neither regime. Code to reproduce the results is available atthis https URL.
  </details>
