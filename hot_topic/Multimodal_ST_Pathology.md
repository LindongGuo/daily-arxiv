# 🔍 Multimodal_ST_Pathology Papers · 2026-10-19

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[spora: A Unified Multimodal Dataset and Platform for Spatial Proteomics](https://arxiv.org/abs/2610.24002)**  `arXiv:2610.24002`  `cs.CV` `cs.AI`  
  _Benedikt von Querfurth, Johann Wenckstern, Eeshaan Jain, Lukas Klein, Phil Cheng, Yexiang Cheng, et al._
  <details open><summary>Abstract</summary>
  Spatial proteomics (SP) captures the molecular composition and spatial organization of tissues at single-cell resolution, opening a direct view of the cellular ecosystems that drive disease. Protein panels, acquisition platforms, and tissue contexts differ from one cohort to the next, and a coherent picture of tissue biology can only emerge from models trained to bridge this heterogeneity. Foundation models offer the natural path forward, but their training depends on large, harmonized corpora that span platforms, panels, and cohorts. No public resource currently approaches that scale; available data sit in small, narrowly scoped releases with incompatible formats and conventions. We present $\texttt{spora}$, a large-scale multimodal SP dataset of 13,546 standardized multiplex images from 5,477 patients across 35 cohorts and five major SP technologies. Curated with biomedical experts, $\texttt{spora}$ provides model training-ready formats together with cell and tissue segmentations, structured clinical metadata, and, where available, paired H&E enabling the training of virtual staining models. It is complemented by $\texttt{spora [io]}$, a unified interface for tiling, sampling, and standardization across all cohorts and modalities, and $\texttt{spora [bench]}$, a benchmark suite spanning cell phenotyping, diagnostic and therapeutic prediction as well as virtual staining tasks across twelve cohorts that places current SP foundation models on common ground against task specific baselines.
  </details>

- **[HGASurv: Hierarchical Granularity-Aware Integration for Multimodal Survival Prediction](https://arxiv.org/abs/2610.26357)**  `arXiv:2610.26357`  `cs.CV`  
  _Peike Yu, Wuchao Liu, Jihong Guan, Shuigeng Zhou_
  <details open><summary>Abstract</summary>
  Objective: Multimodal survival prediction jointly analyzes histopathological whole-slide images (WSIs), genomic profiles, and clinical variables to stratify patients by risk. However, existing approaches often inadequately account for granularity differences across modalities, particularly in spatial organization and feature dimensionality. To address these challenges, we propose HGASurv, which introduces a hierarchical WSI encoding module and a clinical-guided graph propagation module for granularity-aware multimodal integration. Methods: The hierarchical WSI encoding module maps WSI patch features onto a spatial grid using their original coordinates and applies parallel convolutions to construct representations at patch, local-neighborhood, and regional scales. Genomic signature embeddings then query these scale-specific WSI representations through cross-modal co-attention, producing signature-conditioned morphological features. The clinical-guided graph propagation module uses clinical variables to define patient-similarity edges and propagates fused image-genomic node embeddings with graph attention, integrating clinical information through topology rather than feature concatenation. Results: Across three TCGA cohorts, HGASurv achieved the strongest overall C-index performance, with ablation studies supporting the complementary contributions of the hierarchical WSI encoding and clinical-guided graph propagation modules. Conclusion and Significance: By introducing hierarchical WSI encoding and clinical-guided graph propagation, HGASurv unifies multi-scale pathology representation with topology-based clinical integration in a hierarchical granularity-aware framework. This design shows that matching representation and integration mechanisms to modality-specific granularity improves multimodal survival prediction.
  </details>

- **[Pathway-Structured Privileged Distillation for Deployable Computational Pathology](https://arxiv.org/abs/2606.02877)**  `arXiv:2606.02877`  `cs.CV`  
  _Yongxin Guo, Hao Lu, Onur Koyun, Muhammet Demir, Metin Gurcan_
  <details open><summary>Abstract</summary>
  Integrating transcriptomics and histopathology can improve cancer risk modelling, yet practical use is constrained by the limited availability of RNA profiling in routine settings. Here we introduce Mixture of Pathway Experts (MoPE), a knowledge-distillation framework that reframes multimodal learning as privileged distillation for histology-only inference. MoPE is motivated by the partial observability between RNA profiles and whole-slide images: histology can capture morphology-linked consequences of certain molecular programmes, but cannot be expected to reconstruct the full transcriptomic state. MoPE encodes RNA-derived pathways and transfers the molecular supervision to pathway-indexed pathology experts through memory-usage alignment. Across diverse public benchmarks and two independent breast cancer cohorts, MoPE consistently improved WSI-only inference performance relative to baseline methods. Pathway-usage analyses and human-audited visual inspection provide bounded inspection of model behaviour and candidate morphology-linked readouts. These results support pathway-structured privileged distillation as a promising route to using molecular information during training while preserving RNA-free inference.
  </details>
