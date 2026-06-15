# 🔍 Multimodal_ST_Pathology Papers · 2026-06-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[HiST: A Hierarchical Sparse Transformer for Cross-Modal Spatial Transcriptomics Modeling](https://arxiv.org/abs/2606.14251)**  `arXiv:2606.14251`  `cs.CV`  
  _Weiyi Wu, Xinwen Xu, Xingjian Diao, Siting Li, Zhi Wei, Alma Andersson, et al._
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) links gene expression with tissue morphology but remains expensive and low-throughput, motivating surrogates that infer expression from routine histology. Whole-slide H&E-to-ST inference pairs a gigapixel image with gene measurements at a sparse, irregular set of locations, making multiscale modeling challenging without incurring dense-grid overhead or quadratic token mixing. We propose HiST, a hierarchical sparse transformer that treats measured locations as a lattice-indexed sparse field and builds a dyadic encoder--decoder directly on the active tissue footprint. HiST combines sparse window attention for local geometric correspondence with resolution-changing operators for rapid multiscale context integration. For a fixed window size, the dominant runtime and memory scale with the number of observed locations rather than the dense slide area. To mitigate slide-specific acquisition variation, HiST adds a bottlenecked global conditioning pathway via a \emph{slide calibration token} that summarizes slide-level context and conditions local representations. On a multi-organ benchmark spanning diverse tissues and acquisition sources, HiST improves predictive performance over recent baselines while reducing runtime and peak memory.
  </details>
