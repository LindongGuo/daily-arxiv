# 🔍 Med_Foundation_Models Papers · 2026-03-13

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Streamline pathology foundation model by cross-magnification distillation](https://arxiv.org/abs/2509.23097)**  `arXiv:2509.23097`  `cs.CV`  
  _Ziyu Su, Abdul Rehman Akbar, Usama Sajjad, Anil V. Parwani, Muhammad Khalid Khan Niazi_
  <details open><summary>Abstract</summary>
  Foundation models (FM) have transformed computational pathology but remain computationally prohibitive for clinical deployment due to their massive parameter counts and high-magnification processing requirements. Here, we introduce XMAG, a lightweight FM developed through corss-magnification distillation that transfers knowledge from state-of-the-art 20x magnification teacher to an efficient 5x magnification student architecture. XMAG employs a compact backbone and operates entirely at 5x, requiring 11.3 times fewer patches per whole slide image (WSI) compared to existing approaches. Our Novel distillation framework incorporates dual-level knowledge transfer, aligning both global image representations and local spatial token mapping. We trained XMAG on 3.49 million images curated from publicly available datasets and evaluated performance across six clinically relevant histopathology analysis tasks spanning multiple cancer types. XMAG achieved diagnostic accuracy within 1% of substantially larger foundation models while delivering 30-fold processing acceleration, reaching 8.8 WSIs per minute processing speed. Our cross-institutional validation confirmed robust generalization. Further, we developed an end-to-end training strategy to further boost our model's performance to approach the larger FMs' performance. These results establish cross-magnification distillation as a viable approach for deploying FM capabilities in resource-constrained clinical environments, potentially enabling real-time pathology AI integration.
  </details>

- **[SOTA: Self-adaptive Optimal Transport for Zero-Shot Classification with Multiple Foundation Models](https://arxiv.org/abs/2506.13723)**  `arXiv:2506.13723`  `cs.CV`  
  _Zhanxuan Hu, Qiyu Xu, Yu Duan, Yonghang Tai, Huafeng Li_
  <details open><summary>Abstract</summary>
  Foundation models have attracted widespread attention across domains due to their powerful zero-shot classification capabilities. This work is motivated by two key observations: (1) \textit{Vision-Language Models} (VLMs), such as CLIP, often over-rely on class-level textual priors and struggle to capture fine-grained visual cues, whereas \textit{Vision-only Foundation Models} (VFMs), such as DINO, provide rich and discriminative visual features but lack semantic alignment; (2) the performance of different VLMs varies considerably across datasets owing to differences in pre-training. To address these challenges, we propose \textbf{SOTA} (\textit{Self-adaptive Optimal TrAnsport}), a \textit{training-free} ensemble framework that integrates the outputs of multiple foundation models~(VFMs or VLMs) by learning a self-adaptive transport plan. Notably, \textbf{SOTA} is prior-free and automatically balances model contributions. Extensive experiments across diverse domains, including natural images, medical pathology, and remote sensing, validate the generalizability of \textbf{SOTA}. The results consistently show that it effectively leverages the complementary strengths of different foundation models and achieves substantial improvements over individual models. The implementation code is available at:this https URL.
  </details>
