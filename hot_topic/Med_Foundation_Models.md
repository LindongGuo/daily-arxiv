# 🔍 Med_Foundation_Models Papers · 2026-05-26

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
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

- **[On the Role of Inductive Bias in Time-Series Pretraining: A Case Study in Learning Generalizable Representations for Clinical Time Series](https://arxiv.org/abs/2605.26194)**  `arXiv:2605.26194`  `cs.LG`  
  _Sharmita Dey, Diego Paez-Granados_
  <details open><summary>Abstract</summary>
  Clinical time-series learning is routinely constrained by small, heterogeneous cohorts and protocol drift, while its downstream use spans both classification (e.g., pathology diagnosis) and regression (e.g., temporal forecasting). These constraints make foundation-model pretraining appealing, but raises an important question of which inductive biases should the pretraining objective impose so that representations transfer across task types and subjects. We study this question in pathological gait analysis for spinal cord injury (SCI) via PathoFM, an encoder-centric transformer pretrained on multivariate gait windows with three complementary objectives: Local Completion (reconstruct contiguous masked spans to enforce local structure), Temporal Continuity (predict a masked mid-horizon continuation from an observed prefix to enforce smoothness and causal consistency), and Unsupervised In-Context Dynamics (support-query reconstruction conditioned on subject exemplar windows via attention). Empirically comparing objective families (grouping/contrastive, dynamics-based, and generative reconstruction), we find that dynamics-centric mixtures produce the most balanced transfer: grouping objectives favor discriminative margins but can degrade magnitude fidelity needed for continuous targets, whereas reconstruction-only objectives preserve waveform structure but may underperform on classification. Overall, combining local reconstruction with temporal continuity, and adding in-context conditioning when exemplar access is realistic, yields robust subject-generalizing representations.
  </details>
