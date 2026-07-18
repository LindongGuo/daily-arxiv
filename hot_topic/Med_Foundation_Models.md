# 🔍 Med_Foundation_Models Papers · 2026-07-17

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Pretraining Multiple Instance Learning Networks with Multi-Teacher Distillation from Pathology Slide Foundation Models](https://arxiv.org/abs/2607.14703)**  `arXiv:2607.14703`  `cs.CV` `cs.AI`  
  _Mingxi Fu, Jiawen Li, Renao Yan, Jiali Hu, Qiehe Sun, Tian Guan, et al._
  <details open><summary>Abstract</summary>
  Multiple instance learning (MIL) has become the main paradigm for whole-slide image (WSI) analysis in computational pathology. However, existing MIL aggregators are still typically trained from scratch for each downstream task, relying on limited slide-level labels to learn both aggregation mechanisms and downstream discriminative representations simultaneously. As a result, they often suffer from unstable optimization, overfitting, and limited transferability. Similar to pretrained ResNet and Vision Transformer models in natural image learning, MIL also requires reusable pretrained initialization. However, high-quality slide-level pretraining data remain scarce, and MIL models are usually lightweight and weakly supervised, making large-scale pretraining difficult in practice. To address this challenge, we propose a distillation-based pretraining framework for MIL, which leverages two slide-level foundation models, TITAN and CARE, as teachers to transfer their representational knowledge into a diverse set of MIL architectures. To effectively balance supervision from different teachers, we further introduce an angular dispersion normalized distillation loss. The distilled weights are then used as initialization for downstream adaptation. We conduct systematic evaluations on 15 benchmark datasets under both linear probing and full-parameter fine-tuning, and further validate its advantages in few-shot scenarios. Experimental results show that pretraining generally improves MIL aggregators over from scratch training, especially in linear-probing and few-shot settings, while maintaining the computational efficiency of lightweight MIL models. Code is available atthis https URL.
  </details>
