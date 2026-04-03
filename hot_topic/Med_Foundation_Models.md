# 🔍 Med_Foundation_Models Papers · 2026-04-02

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Improvise, Adapt, Overcome -- Telescopic Adapters for Efficient Fine-tuning of Vision Language Models in Medical Imaging](https://arxiv.org/abs/2512.13855)**  `arXiv:2512.13855`  `cs.CV` `cs.AI`  
  _Ujjwal Mishra, Vinita Shukla, Praful Hambarde, Amit Shukla_
  <details open><summary>Abstract</summary>
  Adapting Vision Language Segmentation Models (VLSMs) to medical imaging domains requires significant computational overhead when using conventional fine-tuning approaches. Existing Parameter-Efficient Fine-Tuning (PEFT) methods apply uniform adapter dimensions across all transformer layers, leading to suboptimal parameter allocation and reduced adaptation efficiency. We introduce Telescopic Adapters, a novel PEFT framework that employs depth-aware scaling to progressively increase adapter capacity from shallow to deep transformer layers. Our method integrates lightweight bottleneck modules within CLIPSeg's vision and text encoders, with adapter dimensions dynamically scaled based on layer depth and semantic relevance. Using only 613k trainable parameters--244x fewer than end-to-end fine-tuning, Telescopic Adapters achieve superior performance across five diverse medical datasets spanning polyp segmentation, skin lesion detection, and breast ultrasound imaging. Comprehensive ablation studies demonstrate that deeper layers require substantially more adaptation capacity than shallow layers, validating our telescopic scaling hypothesis. Our approach establishes a new paradigm for efficient medical VLSM fine-tuning, enabling deployment in resource-constrained clinical environments while maintaining competitive segmentation accuracy. Our source code is publicly available atthis https URL
  </details>
