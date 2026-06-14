# 🔍 Med_Foundation_Models Papers · 2026-06-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[BrainDINO: A Brain MRI Foundation Model for Generalizable Clinical Representation Learning](https://arxiv.org/abs/2604.27277)**  `arXiv:2604.27277`  `cs.LG` `cs.AI` `cs.CV`  
  _Yizhou Wu, Shansong Wang, Yuheng Li, Mojtaba Safari, Mingzhe Hu, Chih-Wei Chang, et al._
  <details open><summary>Abstract</summary>
  Brain MRI underpins a wide range of neuroscientific and clinical applications, yet most learning-based methods remain task-specific and require substantial labeled data. Here we show that a single self-supervised representation can generalize across heterogeneous brain MRI endpoints. We trained BrainDINO, a self-distilled foundation model, on approximately 6.6 million unlabeled axial slices from 20 datasets encompassing broad variation in population, disease, and acquisition setting. Using a frozen encoder with lightweight task heads, BrainDINO supported transfer across tumor segmentation, neurodegenerative and neurodevelopmental conditions classification, brain age estimation, post-stroke temporal prediction, molecular status prediction, MRI sequence classification, and survival modeling. Across tasks and supervision regimes, BrainDINO consistently equaled or exceeded natural-image and MRI-specific self-supervised baselines, with particularly strong advantages under label scarcity. Representation analyses further showed anatomically organized and pathology-sensitive feature structure in the absence of task-specific supervision. Our findings indicate that large-scale slice-wise self-supervised learning can yield a unified brain MRI representation that supports diverse neuroimaging tasks without volumetric pretraining or full-network fine-tuning, establishing a scalable foundation for robust and data-efficient brain imaging analysis. Code is available atthis https URL
  </details>
