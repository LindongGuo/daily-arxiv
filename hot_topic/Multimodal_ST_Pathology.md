# 🔍 Multimodal_ST_Pathology Papers · 2026-06-02

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Spatial Transcriptomics-Guided Alignment Enhances Molecular Profiling in Pathology Foundation Model](https://arxiv.org/abs/2606.03644)**  `arXiv:2606.03644`  `cs.LG`  
  _Fengtao Zhou, Yingxue Xu, Zhengyu Zhang, Yihui Wang, Zhengrui Guo, Ling Liang, et al._
  <details open><summary>Abstract</summary>
  Comprehensive molecular profiling is essential for modern precision oncology but remains hindered by prohibitive costs, specimen exhaustion, and protracted turnaround times. While pathology foundation models (PFMs) have demonstrated potential for inferring molecular phenotypes from routine hematoxylin and eosin (H&E) whole-slide images (WSIs), current architectures primarily rely on vision-centric self-supervised learning or vision-language alignment, lacking the spatially resolved molecular supervision required to connect subtle morphological features with underlying genomic alterations. Spatial transcriptomics (ST) emerges as a transformative technology that enables transcriptomic quantification within intact tissue sections, thereby preserving the precise spatial link between histology and molecular profiles. In this study, we present a Spatial Transcriptomics-guided Alignment framework for Molecular Profiling (STAMP), which endows PFMs with intrinsic molecular awareness. To support this paradigm, we curated HumanST-1k, a human ST dataset spanning diverse anatomical organs and sequencing platforms. This atlas yields 1.8 million pairs of H&E patches and corresponding transcriptomic profiles, providing a corpus that links histological structures with their molecular states. To mitigate the technical noise inherent to raw transcriptomics, STAMP applies a pathway-informed alignment strategy that aggregates transcriptomic data into biologically functional pathways, which are subsequently integrated into PFMs via parameter-efficient fine-tuning. This alignment enriches the representation space of PFMs and unlocks their capacity to resolve sub-visual molecular signatures. The clinical utility of these augmented representations was validated through a multi-tier evaluation framework.
  </details>

- **[Pathway-Structured Privileged Distillation for Deployable Computational Pathology](https://arxiv.org/abs/2606.02877)**  `arXiv:2606.02877`  `cs.CV`  
  _Yongxin Guo, Hao Lu, Onur Koyun, Zhengjie Zhu, Muhammet Demir, Metin Gurcan_
  <details open><summary>Abstract</summary>
  Integrating transcriptomics and histopathology can improve cancer risk modelling, yet practical use is constrained by the limited availability of RNA profiling in routine settings. Here we introduce Mixture of Pathway Experts (MoPE), a knowledge-distillation framework that reframes multimodal learning as privileged distillation for histology-only inference. MoPE is motivated by the partial observability between RNA profiles and whole-slide images: histology can capture morphology-linked consequences of certain molecular programmes, but cannot be expected to reconstruct the full transcriptomic state. MoPE encodes RNA-derived pathways and transfers the molecular supervision to pathway-indexed pathology experts through memory-usage alignment. Across diverse public benchmarks and two independent breast cancer cohorts, MoPE consistently improved WSI-only inference performance relative to baseline methods. Pathway-usage analyses and human-audited visual inspection provide bounded inspection of model behaviour and candidate morphology-linked readouts. These results support pathway-structured privileged distillation as a promising route to using molecular information during training while preserving RNA-free inference.
  </details>
