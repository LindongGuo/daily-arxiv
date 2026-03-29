# 🔍 Med_Foundation_Models Papers · 2026-03-28

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[CORA: A Pathology Synthesis Driven Foundation Model for Coronary CT Angiography Analysis and MACE Risk Assessment](https://arxiv.org/abs/2603.24847)**  `arXiv:2603.24847`  `cs.CV`  
  _Jinkui Hao, Gorkem Durak, Halil Ertugrul Aktas, Ulas Bagci, Bradley D. Allen, Nilay S. Shah, et al._
  <details open><summary>Abstract</summary>
  Coronary artery disease, the leading cause of cardiovascular mortality worldwide, can be assessed non-invasively by coronary computed tomography angiography (CCTA). Despite progress in automated CCTA analysis using deep learning, clinical translation is constrained by the scarcity of expert-annotated datasets. Furthermore, widely adopted label-free pretraining strategies, such as masked image modeling, are intrinsically biased toward global anatomical statistics, frequently failing to capture the spatially localized pathological features of coronary plaques. Here, we introduce CORA, a 3D vision foundation model for comprehensive cardiovascular risk assessment. CORA learns directly from volumetric CCTA via a pathology-centric, synthesis-driven self-supervised framework. By utilizing an anatomy-guided lesion synthesis engine, the model is explicitly trained to detect simulated vascular abnormalities, biasing representation learning toward clinically relevant disease features rather than dominant background anatomy. We trained CORA on a large-scale cohort of 12,801 unlabeled CCTA volumes and comprehensively evaluated the model across multi-center datasets from nine independent hospitals. Across diagnostic and anatomical tasks, including plaque characterization, stenosis detection, and coronary artery segmentation, CORA consistently outperformed the state-of-the-art 3D vision foundation models, achieving up to a 29\% performance gain. Crucially, by coupling the imaging encoder with a large language model, we extended CORA into a multimodal framework that significantly improved 30-day major adverse cardiac event (MACE) risk stratification. Our results establish CORA as a scalable and extensible foundation for unified anatomical assessment and cardiovascular risk prediction.
  </details>
