# 🔍 Med_Foundation_Models Papers · 2026-07-13

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[LaGuadia: Language-Guided Adaptive Distillation from Pathology Foundation Models](https://arxiv.org/abs/2607.11257)**  `arXiv:2607.11257`  `cs.CV` `cs.LG`  
  _Gangsu Kim, Won-Ki Jeong_
  <details open><summary>Abstract</summary>
  Pathology Foundation Models (PFMs) offer powerful Whole Slide Image (WSI) representations but suffer from massive computational costs. While Knowledge Distillation (KD) can create efficient student models, existing multi-teacher methods often use suboptimal uniform weighting that ignores tissue heterogeneity. We propose LaGuadia (Language-Guided Adaptive DistillAtion), a framework that develops a compact pathology image encoder by dynamically integrating expertise from multiple PFMs under clinical linguistic guidance. Our approach utilizes a multi-stage pipeline: first, extracting visually observable clinical keywords from pathology reports; second, aligning visual features with these keywords via a Vision-Language meta-teacher (MedSigLIP) to provide dense semantic guidance; and finally, performing adaptive KD where teacher contributions are weighted based on their semantic alignment with the clinical narrative. Experiments on WSI captioning, visual question answering, and slide-level classification tasks demonstrate that an 87M parameter LaGuadia student model matches or exceeds foundation-scale models such as GigaPath and UNI, achieving strong factual consistency and robust generalization. These results highlight clinical language as an effective semantic anchor for building efficient and reliable digital pathology systems. Code is available atthis https URL.
  </details>

- **[TVT-PAPD: Pathology-Aware Prototype Distillation for Self-Supervised Whole Slide Image Classification](https://arxiv.org/abs/2607.10406)**  `arXiv:2607.10406`  `cs.CV` `cs.LG`  
  _Ramesh Naidu Laveti, Jaya Sreevalsan-Nair, T K Srikanth_
  <details open><summary>Abstract</summary>
  Self-supervised learning (SSL) has emerged as an effective paradigm for learning transferable representations from large-scale unlabeled whole slide images (WSIs). However, existing SSL methods primarily learn generic visual features and often fail to explicitly capture pathology-specific morphological patterns that are critical for disease characterization. To address this limitation, we propose Tiny Vision Transformer with Pathology-Aware Prototype Distillation (TVT-PAPD). This self-supervised pathology representation learning framework integrates a Tiny Vision Transformer (TVT) with a novel Pathology-Aware Prototype Distillation (PAPD) module. PAPD employs a learnable pathology prototype bank to discover and preserve representative tissue morphology patterns, encouraging semantically similar pathological regions to learn consistent and discriminative representations. The proposed framework enhances pathology-aware feature learning while maintaining computational efficiency with 90M parameters. Experiments on the Cancer Genome Atlas (TCGA) low-grade glioma (LGG)/glioblastoma (GBM) dataset and the Indian Pathology Brain (IPD-Brain) dataset demonstrate that TVT-PAPD achieves weighted F1-scores of 93.02% and 90.23%, respectively, for LGG-GBM classification, while exhibiting strong cross-cohort generalization across independent glioma datasets.
  </details>

- **[Learning To Focus: Anatomy-Guided Attention Regularization for Medical Image Classification](https://arxiv.org/abs/2607.10851)**  `arXiv:2607.10851`  `cs.CV`  
  _Tonmoy Hossain, Atiqur Rahman, Farhana Hossain Swarnali, Miaomiao Zhang_
  <details open><summary>Abstract</summary>
  Medical image classification models are ideally expected to identify diagnostically relevant regions while making predictions, yet standard classification losses rarely provide spatial supervision. Explicit supervision via anatomical shape information, such as segmentation masks of task-relevant anatomy, has been shown to guide the network toward regions relevant to the target prediction. However, obtaining such masks incurs substantial manual annotation effort and computational overhead. With the advent of segmentation foundation models that exhibit strong localization of anatomical structures across diverse imaging modalities, we leverage this capability to extract anatomical shape priors without the burden of training a dedicated segmentation model. In this paper, we propose a new framework, Locus, an anatomical attention regularization framework that leverages pretrained segmentation foundation models to guide a classifier's attention toward diagnostically meaningful anatomical structures across diverse imaging modalities. Instead of enforcing pixel-wise alignment with the foundation-model-derived mask, we introduce a regularization term that adaptively balances attention between anatomical (foreground) and background regions, penalizing the classifier when background attention dominates. We validate Locus on eight diverse medical imaging datasets spanning dermoscopy, X-ray, histopathology, and cardiac MRI, showing consistent gains in classification performance alongside improved anatomically grounded attention.
  </details>
