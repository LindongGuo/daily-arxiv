# 🔍 Med_Foundation_Models Papers · 2026-03-11

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[SOTA: Self-adaptive Optimal Transport for Zero-Shot Classification with Multiple Foundation Models](https://arxiv.org/abs/2506.13723)**  `arXiv:2506.13723`  `cs.CV`  
  _Zhanxuan Hu, Qiyu Xu, Yu Duan, Yonghang Tai, Huafeng Li_
  <details open><summary>Abstract</summary>
  Foundation models have attracted widespread attention across domains due to their powerful zero-shot classification capabilities. This work is motivated by two key observations: (1) \textit{Vision-Language Models} (VLMs), such as CLIP, often over-rely on class-level textual priors and struggle to capture fine-grained visual cues, whereas \textit{Vision-only Foundation Models} (VFMs), such as DINO, provide rich and discriminative visual features but lack semantic alignment; (2) the performance of different VLMs varies considerably across datasets owing to differences in pre-training. To address these challenges, we propose \textbf{SOTA} (\textit{Self-adaptive Optimal TrAnsport}), a \textit{training-free} ensemble framework that integrates the outputs of multiple foundation models~(VFMs or VLMs) by learning a self-adaptive transport plan. Notably, \textbf{SOTA} is prior-free and automatically balances model contributions. Extensive experiments across diverse domains, including natural images, medical pathology, and remote sensing, validate the generalizability of \textbf{SOTA}. The results consistently show that it effectively leverages the complementary strengths of different foundation models and achieves substantial improvements over individual models. The implementation code is available at:this https URL.
  </details>

- **[Leveraging Spatial Context for Positive Pair Sampling in Histopathology Image Representation Learning](https://arxiv.org/abs/2503.05170)**  `arXiv:2503.05170`  `cs.CV`  
  _Willmer Rafell Quinones Robles, Sakonporn Noree, Jongwoo Kim, Young Sin Ko, Bryan Wong, Mun Yong Yi_
  <details open><summary>Abstract</summary>
  Deep learning has shown strong potential in cancer classification from whole-slide images (WSIs), but the need for extensive expert annotations often limits its success. Annotation-free approaches, such as multiple instance learning (MIL) and self-supervised learning (SSL), have emerged as promising alternatives to traditional annotation-based methods. However, conventional SSL methods typically rely on synthetic data augmentations, which may fail to capture the spatial structure critical to histopathology. In this work, we propose a spatial context-driven positive pair sampling strategy that enhances SSL by leveraging the morphological coherence of spatially adjacent patches within WSIs. Our method is modular and compatible with established joint embedding SSL frameworks, including Barlow Twins, BYOL, VICReg, and DINOv2. We evaluate its effectiveness on both slide-level classification using MIL and patch-level linear probing. Experiments across four datasets demonstrate consistent performance improvements, with accuracy gains of 5\% to 10\% compared to standard augmentation-based sampling. These findings highlight the value of spatial context in improving representation learning for computational pathology and provide a biologically meaningful enhancement for pretraining models in annotation-limited settings. The code is available atthis https URL.
  </details>
