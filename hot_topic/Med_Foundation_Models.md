# 🔍 Med_Foundation_Models Papers · 2026-05-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Anatomy-Guided Vision-Language Learning with Angular Prototype Separation for Multi-Label Video Capsule Endoscopy Classification Under Class Imbalance](https://arxiv.org/abs/2603.17879)**  `arXiv:2603.17879`  `cs.CV` `cs.AI`  
  _Podakanti Satyajith Chary, Nagarajan Ganapathy_
  <details open><summary>Abstract</summary>
  This work presents a multi-label temporal event detection framework for video capsule endoscopy (VCE) that addresses the extreme class imbalance inherent in the Galar dataset by combining two principal contributions: an Angular Separation Loss on class prototypes and a Biological State Machine temporal decoder. The backbone remains BiomedCLIP, a biomedical vision-language foundation model. Three consecutive frames are fused through a Local Differencing Attention module that amplifies transient pathological signals by suppressing static temporal redundancy. An Anatomy Context Head then conditions pathological predictions on soft anatomical activations, exploiting the known spatial co-occurrence structure of GI findings. Learnable text-feature prompts and prototype-based logit augmentation are trained alongside an Angular Separation Loss that penalizes off-diagonal cosine similarity between class prototypes, preventing the prototype collapse that afflicts rare classes under extreme imbalance. To counteract the skewed label distribution, the training regime combines asymmetric focal loss, inverse-frequency weighted sampling, temporal Mixup, Exponential Moving Average, and per-class threshold calibration. The Biological State Machine decoder replaces naive gap merging with a physiologically grounded forward-only state transition over anatomy labels, eliminating the fragmentation artefact that produced hundreds of spurious anatomy events per video in the prior approach and reducing per-video anatomy output to 2--3 clinically realistic events. On the held-out RARE-VISION test set comprising three NaviCam examinations (161,025 frames), the updated pipeline achieves an overall temporal mAP@0.5 of 0.3597 and mAP@0.95 of 0.3399, representing a relative improvement of 46% and 44% respectively over the prior submission, with total inference completed in approximately 21 minutes on a single GPU.
  </details>

- **[MedSAE: Dissecting MedCLIP Representations with Sparse Autoencoders](https://arxiv.org/abs/2510.26411)**  `arXiv:2510.26411`  `cs.AI`  
  _Riccardo Renzulli, Colas Lepoutre, Enrico Cassano, Marco Grangetto_
  <details open><summary>Abstract</summary>
  Artificial intelligence in healthcare requires models that are accurate and interpretable. We advance mechanistic interpretability in medical vision by applying Medical Sparse Autoencoders (MedSAEs) to the latent space of MedCLIP, a vision-language model trained on chest radiographs and reports. To quantify interpretability, we propose an evaluation framework that combines correlation metrics, entropy analyses, and automated neuron naming via the MedGemma foundation model. Experiments on the CheXpert dataset show that MedSAE neurons achieve higher monosemanticity and interpretability than raw MedCLIP features. Our findings bridge high-performing medical AI and transparency, offering a scalable step toward clinically reliable representations. The source code supporting the findings of this study is available atthis https URL.
  </details>
