# 🔍 Med_Foundation_Models Papers · 2026-05-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[M-IDoL: Information Decomposition for Modality-Specific and Diverse Representation Learning in Medical Foundation Model](https://arxiv.org/abs/2604.08936)**  `arXiv:2604.08936`  `cs.CV`  
  _Yihang Liu, Longzhen Yang, Jiaxiong Yang, Ying Wen, Lianghua He, Heng Tao Shen_
  <details open><summary>Abstract</summary>
  Medical foundation models (MFMs) aim to learn universal representations from multimodal medical images that can generalize effectively to diverse downstream clinical tasks. However, most existing MFMs suffer from information ambiguity that blends multimodal representations in a single embedding space, leading to the degradation of modality specificity and diversity. In this paper, we propose M-IDoL, a self-supervised MFM that introduces Information Decomposition for multimodal representation Learning via two objectives: i) maximizing inter-modality entropy by dispersing multimodal representations into separable Mixture-of-Experts (MoE) subspaces to achieve representation specificity across modalities; and ii) minimizing intra-modality uncertainty by performing fine-grained semantic discrimination within each MoE subspace to enrich representation diversity per modality. By pre-training on 1.15 million medical images, M-IDoL i) delivers superior generalization across 21 downstream clinical tasks, outperforming 20 foundation models on five imaging modalities (e.g., X-ray, fundus, OCT, dermoscopy and pathology), and ii) learns modality-specific and diverse representations, showing clearer separation of feature clusters across modalities and finer-grained feature discrimination within each modality.
  </details>

- **[Supervise Less, See More: Training-free Nuclear Instance Segmentation with Prototype-Guided Prompting](https://arxiv.org/abs/2511.19953)**  `arXiv:2511.19953`  `cs.CV`  
  _Wen Zhang, Qin Ren, Wenjing Liu, Haibin Ling, Chenyu You_
  <details open><summary>Abstract</summary>
  Accurate nuclear instance segmentation is a pivotal task in computational pathology, supporting data-driven clinical insights and facilitating downstream translational applications. While large vision foundation models have shown promise for zero-shot biomedical segmentation, most existing approaches still depend on dense supervision and computationally expensive fine-tuning. Consequently, training-free methods present a compelling research direction, yet remain largely unexplored. In this work, we introduce SPROUT, a fully training- and annotation-free prompting framework for nuclear instance segmentation. SPROUT leverages histology-informed priors to construct slide-specific reference prototypes that mitigate domain gaps. These prototypes progressively guide feature alignment through a partial optimal transport scheme. The resulting foreground and background features are transformed into positive and negative point prompts, enabling the Segment Anything Model (SAM) to produce precise nuclear delineations without any parameter updates. Extensive experiments across multiple histopathology benchmarks demonstrate that SPROUT achieves competitive performance without supervision or retraining, establishing a novel paradigm for scalable, training-free nuclear instance segmentation in pathology.
  </details>
