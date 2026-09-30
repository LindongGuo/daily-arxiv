# 🔍 ST_Generation_Imputation Papers · 2026-09-29

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Towards Scalable Context-Aware Single-Cell Spatial Transcriptomics Prediction from Histology Images](https://arxiv.org/abs/2609.36429)**  `arXiv:2609.36429`  `cs.CV`  
  _Zijun Gao, Chunbin Gu, Jinxi Xiang, Xiangde Luo, Pheng-Ann Heng_
  <details open><summary>Abstract</summary>
  Predicting gene expression from H&E-stained histology images offers a scalable alternative to costly spatial transcriptomics, yet most existing methods operate at the spot level, where signals from multiple cells are aggregated and critical cellular heterogeneity is obscured. Extending this paradigm to single-cell resolution is non-trivial. Naively applying pathology foundation models faces a scale mismatch: their patch-level representations mix multiple cells, whereas per-cell cropping or resizing distorts morphology and removes local context. Conversely, segmentation-based models without strong pretrained visual encoders often lack the morphological representation capacity needed for accurate molecular prediction and inherit errors from imperfect cell boundary masks. Here, we present CELLO, an efficient end-to-end framework that performs a single pathology foundation model forward pass per image and uses grid sampling to extract location-specific features for all cells simultaneously. We further introduce a distance-decay cross-attention module that refines each cell representation using spatially biased local morphological context. Using 52 public Xenium-H&E pairs from HEST-1k that span 12 organs and approximately 10 million cells, CELLO improves the average predictive accuracy over the evaluated baselines while reducing the mean whole-slide inference time compared to DeepSpot2Cell, a 14.0x speed-up on average that excludes upstream cell segmentation. Our work establishes a scalable foundation for single-cell gene expression prediction from H&E images.
  </details>

- **[Language as the Interface: Foundation-Model Contrastive Learning Links Transcriptomes and Electrophysiology](https://arxiv.org/abs/2609.37024)**  `arXiv:2609.37024`  `cs.AI`  
  _Junbo Shen, Jinying Gao, Bo Lei_
  <details open><summary>Abstract</summary>
  Integrating transcriptomic and electrophysiological data is essential for building multimodal foundation models for neuroscience. Patch-seq provides paired measurements of gene expression and intrinsic electrophysiology from the same neuron, establishing a basis for training cross-modal models. Here we introduce LangPatch, a foundation-model-based contrastive learning framework that uses paired Patch-seq data to align pretrained GenePT representations with electrophysiological phenotypes through a language-based interface. Gene descriptions and verbalized electrophysiological profiles are embedded by the same frozen text encoder. A context adapter and projection modules connect the modalities through paired contrastive learning. Across mouse visual, mouse motor, and human cortical cohorts, LangPatch achieves the highest mean transcriptome-to-electrophysiology prediction correlation among the evaluated foundation-model and representation-learning methods. It also improves held-out cross-modal alignment in the two mouse cohorts (FOSCTTM 0.107/0.135 vs. 0.208/0.222 for JAMIE, an existing cross-modal Patch-seq imputation method). It predicts transcriptomic family, type, cortical layer, and marker-gene expression from electrophysiology, exceeding other baselines on most endpoints. More importantly, the method transfers across brain areas and species: a model trained on mouse visual cortex predicts electrophysiology in motor cortex with approximately 70% correlation retention and in human cortex with 47% (58% on acute-slice recordings). Together, these results demonstrate alignment between molecular and functional representations of neurons, providing a building block for multimodal foundation models in neuroscience.
  </details>
