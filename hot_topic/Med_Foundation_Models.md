# 🔍 Med_Foundation_Models Papers · 2026-07-12

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[ALICE: Learning a General-Purpose Pathology Foundation Model from Vision, Vision-Language, and Slide-Level Experts](https://arxiv.org/abs/2607.09526)**  `arXiv:2607.09526`  `cs.CV` `cs.AI`  
  _Jiawen Li, Tian Guan, Huijuan Shi, Xitong Ling, Mingxi Fu, Anjia Han, et al._
  <details open><summary>Abstract</summary>
  Foundation models are reshaping computational pathology, yet their capabilities remain shaped by pretraining objectives, data sources, and spatial scales, fragmenting complementary expertise across separate backbones. Here we present ALICE, a unified foundation model trained through multi-stage agglomerative distillation that sequentially distills eight vision-only, vision-language, and slide-level teacher models into dedicated modules of a single backbone. ALICE is pretrained on 24,985,184 tile-level pathology images and 155,604 high-resolution images, and evaluated across 21 task scenarios, 96 downstream tasks, and 48 data sources, spanning region-of-interest tissue analysis, vision-language multimodal evaluation, and whole-slide clinical assessment. In all three evaluation settings, ALICE achieved the best average rank among task-matched pathology foundation models. These results demonstrate that agglomerative distillation can consolidate complementary capabilities from specialized models into a unified backbone for broad computational pathology applications. The model is available atthis https URL.
  </details>
