# 🔍 Multimodal_ST_Pathology Papers · 2026-09-17

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Bridging Modalities on the Cortex: Surface-based MRI to PET Translation with a Diffusion Bridge](https://arxiv.org/abs/2609.20147)**  `arXiv:2609.20147`  `cs.CV` `cs.AI`  
  _Yitong Li, Alexandra Samoylova, Fabian Bongratz, Timo Grimmer, Dennis M. Hedderich, Igor Yakushev, et al._
  <details open><summary>Abstract</summary>
  Cortical hypometabolism measured by Fluorodeoxyglucose Positron Emission Tomography (FDG-PET) is a highly sensitive biomarker for dementia diagnosis. However, high costs, radiation exposure, and limited accessibility constrain its clinical utility. While cross-modal synthesis from Magnetic Resonance Imaging (MRI) offers a promising alternative, existing volumetric generation methods do not explicitly account for the highly folded cortical geometry, where disease-related patterns predominantly reside. To address this, we introduce a novel surface-based diffusion bridge framework DB-SUiT for MRI-to-PET translation that operates natively on the cortical manifold. A conditional Spherical U-shaped vision Transformer (SUiT) is specifically designed to model the intricate cross-modal relationships while preserving surface topology. It combines spherical convolutional encoders for multi-scale surface feature extraction with bottleneck Transformers to capture long-range spatial dependencies, while incorporating demographic and subcortical conditions to refine the synthesis. Evaluated on two datasets, including subjects with different dementia types, DB-SUiT demonstrates high-fidelity synthesis that substantially outperforms other baselines. In automated dementia classification, synthesized PET surfaces improve performance over MRI by 14.2% and PET volumes by 11.3%, approaching the performance of real PET surfaces. In a blinded reader study, synthetic PET achieved 85.5% diagnostic accuracy, compared with 75.8% for MRI and 95.2% for real PET. This further demonstrates cross-cohort and cross-pathology generalization, as the model was evaluated without retraining on an external cohort that included a dementia subtype not represented during training. Our code is available atthis https URL.
  </details>
