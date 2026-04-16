# 🔍 Med_Foundation_Models Papers · 2026-04-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[CLIP Architecture for Abdominal CT Image-Text Alignment and Zero-Shot Learning: Investigating Batch Composition and Data Scaling](https://arxiv.org/abs/2604.13561)**  `arXiv:2604.13561`  `cs.CV` `cs.AI`  
  _Shivika, Kartik Bose, Pankaj Gupta_
  <details open><summary>Abstract</summary>
  Vision-language models trained with contrastive learning on paired medical images and reports show strong zero-shot diagnostic capabilities, yet the effect of training batch composition on learned representations remains unexplored for 3D medical imaging. We reproduce Merlin, a dual-encoder model that aligns 3D abdominal CT volumes with radiology reports using symmetric InfoNCE loss, achieving a zero-shot macro F1 of 74.45% across 30 findings (original: 73.00%). We then investigate two axes of variation. First, we control the normal-to-abnormal ratio within training batches at 25:75, 50:50, and 75:25 using section-level balanced sampling on the full dataset. All three configurations underperform the unbalanced baseline by 2.4 to 2.8 points, with 75:25 achieving the best result (72.02%) among balanced variants. Second, we conduct data scaling ablations on a 4,362-study subset, training with 20%, 40%, and 100% of the data. Performance scales sub-linearly from 65.26% to 71.88%, with individual findings varying dramatically in data sensitivity. Enforcing 50:50 balanced sampling on the same subset further degrades performance to 68.01%, confirming that explicit class balancing hurts regardless of dataset or balancing granularity. Our results indicate that the stochastic diversity of random sampling, combined with Merlin's alternating batching over anatomical subsections, provides more effective regularization than engineered class ratios at the small batch sizes required by 3D medical volumes.
  </details>
