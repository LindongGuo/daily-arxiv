# 🔍 Med_Foundation_Models Papers · 2026-06-02

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Spatial Transcriptomics-Guided Alignment Enhances Molecular Profiling in Pathology Foundation Model](https://arxiv.org/abs/2606.03644)**  `arXiv:2606.03644`  `cs.LG`  
  _Fengtao Zhou, Yingxue Xu, Zhengyu Zhang, Yihui Wang, Zhengrui Guo, Ling Liang, et al._
  <details open><summary>Abstract</summary>
  Comprehensive molecular profiling is essential for modern precision oncology but remains hindered by prohibitive costs, specimen exhaustion, and protracted turnaround times. While pathology foundation models (PFMs) have demonstrated potential for inferring molecular phenotypes from routine hematoxylin and eosin (H&E) whole-slide images (WSIs), current architectures primarily rely on vision-centric self-supervised learning or vision-language alignment, lacking the spatially resolved molecular supervision required to connect subtle morphological features with underlying genomic alterations. Spatial transcriptomics (ST) emerges as a transformative technology that enables transcriptomic quantification within intact tissue sections, thereby preserving the precise spatial link between histology and molecular profiles. In this study, we present a Spatial Transcriptomics-guided Alignment framework for Molecular Profiling (STAMP), which endows PFMs with intrinsic molecular awareness. To support this paradigm, we curated HumanST-1k, a human ST dataset spanning diverse anatomical organs and sequencing platforms. This atlas yields 1.8 million pairs of H&E patches and corresponding transcriptomic profiles, providing a corpus that links histological structures with their molecular states. To mitigate the technical noise inherent to raw transcriptomics, STAMP applies a pathway-informed alignment strategy that aggregates transcriptomic data into biologically functional pathways, which are subsequently integrated into PFMs via parameter-efficient fine-tuning. This alignment enriches the representation space of PFMs and unlocks their capacity to resolve sub-visual molecular signatures. The clinical utility of these augmented representations was validated through a multi-tier evaluation framework.
  </details>

- **[Task-Aligned Self-Supervised Learning for Medical Image Analysis: A Systematic Review and Practical Design Guidelines](https://arxiv.org/abs/2605.23995)**  `arXiv:2605.23995`  `cs.CV` `cs.AI`  
  _Chathura Wimalasiri, Kishor Nandakishor, Marimuthu Palaniswami_
  <details open><summary>Abstract</summary>
  Self-supervised learning (SSL) has emerged as a promising paradigm for addressing the annotation bottleneck in medical imaging by learning representations from unlabeled data. However, its effectiveness depends heavily on the design of the pretext task and its alignment with the downstream clinical-objectives. We present a systematic, task-oriented review of SSL in medical imaging, examining how different pretext-task formulations influence performance across classification, segmentation, detection, and other tasks. Following PRISMA guidelines, we analyze 75 studies published between 2017 and 2025 and organize them into four paradigms: contrastive, non-contrastive and predictive, generative and reconstruction-based, and hybrid learning. Rather than cataloguing methods by architecture, we map each paradigm to the downstream objectives it best supports. Our analysis shows there is no universally optimal SSL strategy; instead, performance is governed by the alignment between the pretext task, the imaging modality, and the target task. Contrastive methods learn global discriminative features and align well with classification, but may overlook subtle pathological patterns. Generative and spatial prediction-based approaches better preserve local anatomical structure, making them more suitable for segmentation and other dense prediction tasks, while hybrid methods offer the most balanced performance. We further show that modality-specific design is critical and that SSL provides its greatest benefit in low-label and few-shot regimes. Finally, we distill these findings into practical design guidelines and outline open challenges, including pathology-aware pretext task design, resource-efficient training for high-dimensional data, and standardized evaluation protocols. This work offers practical guidance for designing more effective and clinically relevant SSL frameworks in medical imaging.
  </details>
