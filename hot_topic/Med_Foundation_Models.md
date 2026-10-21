# 🔍 Med_Foundation_Models Papers · 2026-10-20

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Convergent Performance, Divergent Mechanisms in LoRA-Adapted Vision Foundation Models for Brain MRI](https://arxiv.org/abs/2610.28255)**  `arXiv:2610.28255`  `cs.CV` `cs.LG`  
  _Cecilia Diana-Albelda, Fiona Kekwick, Raghav Mehta, Aleksandra Kulbaka, Paul M. Matthews, Jesus Bescos, et al._
  <details open><summary>Abstract</summary>
  Adapting Vision Foundation Models (VFMs) to medical imaging via LoRA has become standard practice, yet model selection is guided almost entirely by downstream task metrics, treating backbones with similar performance as interchangeable. We investigate whether equal performance implies equal internal representational shift. We analyse four ViT-B/16 backbones, DINOv3, SigLIP2, MerMED-FM, and BiomedCLIP, pre-trained with different objectives (self-distillation vs. contrastive vision-language) and on different data domains (natural vs. medical images). We adapt each to brain tumour segmentation and evaluate on six datasets covering both segmentation and Alzheimer's disease classification. Using attention divergence, weight-change analysis, and activation patching, we find that the four models converge to similar segmentation performance (mean Dice 78-81%) through markedly different internal dynamics, yet diverge in cross-task transfer: segmentation adaptation improves Alzheimer's disease classification for DINOv3 but degrades it for the other three backbones. We reveal a dissociation between modification magnitude and causal importance: the most heavily modified layers are not the causally relevant ones, with early-to-mid layers identified as sufficient for segmentation recovery. Restricting LoRA to these layers matches or approaches full-layer segmentation while reducing classification degradation in the three affected backbones, providing a mechanistically grounded strategy that is more parameter-efficient and more robust than standard full-layer adaptation.
  </details>

- **[AdaptMIL: Domain Adaptation for Multiple Instance Learning in Digital Pathology](https://arxiv.org/abs/2610.28007)**  `arXiv:2610.28007`  `cs.CV`  
  _Ben Vardi, Dana Schonberger, Yuval Friedmann, Zohar Yakhini, Iris Barshack, Alexander Loebel, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) support a wide range of histopathology tasks on whole-slide images through multiple instance learning (MIL). Despite recent progress, these models remain sensitive to cross-hospital distribution shifts: performance often degrades when a task head (e.g., classification) is trained on data from one hospital and then used on data from another hospital. To address this challenge, we propose AdaptMIL, a training strategy for integrating domain adaptation into MIL training. AdaptMIL is motivated by our finding that directly applying domain adaptation objectives during MIL training can interfere with MIL aggregation learning, often resulting in performance degradation over standard training. AdaptMIL resolves this by decoupling representation-level domain alignment learning from MIL aggregation learning through a two-stage training procedure. We show that AdaptMIL improves cross-hospital performance and outperforms alternative adaptation methods across experiments spanning multiple WSI datasets, tasks, PFMs, MIL architectures, and domain adaptation objectives. AdaptMIL's code will be released upon publication.
  </details>

- **[REST: Reliability-Guided Spatial Transcriptomics Supervision for Gene Expression Prediction from Histopathological HE-Stained Images](https://arxiv.org/abs/2610.26988)**  `arXiv:2610.26988`  `cs.CV`  
  _Lanfeng Zhong, Xiangyu Sun, Guixuan Xu, Rongzhao Zhang, Jie Xu, Shaoting Zhang, et al._
  <details open><summary>Abstract</summary>
  Histopathology is central to cancer diagnosis, but morphology in Hematoxylin and Eosin (HE)-stained images does not directly reveal the molecular states that characterize disease heterogeneity and inform tumor characterization, prognostic assessment, and biomarker discovery. Spatial Transcriptomics (ST) measures spatially resolved gene expression, providing molecular information within tissue architecture, yet differences in assay coverage and spot informativeness make paired HE--ST observations unequally reliable for representation learning. We propose Reliability-Guided Spatial Transcriptomics (REST) supervision with Biological Program Bank (BPB), a program-structured and reliability-guided ST-supervised training framework for predicting molecular information from H\&E images. REST constructs BPB from curated signature, pathway, and cell-type gene sets to provide a shared structure for ST encoding, reliability estimation, and molecular reconstruction. Guided by BPB, Spot-Reliability Contrastive Alignment (SRCA) measures the reliability of each spot from assay-level program coverage and spot-level activity dispersion, and reweights HE--ST alignment accordingly. Biology-Informed Program Reconstruction (BIPR) further uses learnable program queries to reconstruct member-gene expression from histological morphology. REST's training corpus comprised 209 samples (407,475 spots across 16 organs); evaluation used 70 disjoint samples (230,056 spots across eight organs) for gene-expression, pathway-activity, and cell-signature prediction. REST achieved the highest Macro correlation among state-of-the-art ST-supervised training methods and outperformed existing pathology foundation models. Code is available atthis https URL.
  </details>
