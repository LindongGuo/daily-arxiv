# 🔍 Prognosis_Survival Papers · 2026-03-27

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[XtraLight-MedMamba for Classification of Neoplastic Tubular Adenomas](https://arxiv.org/abs/2602.04819)**  `arXiv:2602.04819`  `cs.CV` `cs.LG`  
  _Aqsa Sultana, Rayan Afsar, Ahmed Rahu, Surendra P. Singh, Brian Shula, Brandon Combs, et al._
  <details open><summary>Abstract</summary>
  Accurate risk stratification of precancerous polyps during routine colonoscopy screening is a key strategy to reduce the incidence of colorectal cancer (CRC). However, assessment of low-grade dysplasia remains limited by subjective histopathologic interpretation. Advances in computational pathology and deep learning offer new opportunities to identify subtle, fine morphologic patterns associated with malignant progression that may be imperceptible to the human eye. In this work, we propose XtraLight-MedMamba, an ultra-lightweight state-space-based deep learning framework to classify neoplastic tubular adenomas from whole-slide images (WSIs). The architecture is a blend of a ConvNeXt-based shallow feature extractor with parallel vision mamba blocks to efficiently model local texture cues within global contextual structure. An integration of the Spatial and Channel Attention Bridge (SCAB) module enhances multiscale feature extraction, while the Fixed Non-Negative Orthogonal Classifier (FNOClassifier) enables substantial parameter reduction and improved generalization. The model was evaluated on a curated dataset acquired from patients with low-grade tubular adenomas, stratified into case and control cohorts based on subsequent CRC development. XtraLight-MedMamba achieved an accuracy of 97.18\% and an F1-score of 0.9767 using approximately 32,000 parameters, outperforming transformer-based and conventional Mamba architectures, which have significantly higher model complexity and computational burden, making it suitable for resource-constrained areas.
  </details>

- **[CORA: A Pathology Synthesis Driven Foundation Model for Coronary CT Angiography Analysis and MACE Risk Assessment](https://arxiv.org/abs/2603.24847)**  `arXiv:2603.24847`  `cs.CV`  
  _Jinkui Hao, Gorkem Durak, Halil Ertugrul Aktas, Ulas Bagci, Bradley D. Allen, Nilay S. Shah, et al._
  <details open><summary>Abstract</summary>
  Coronary artery disease, the leading cause of cardiovascular mortality worldwide, can be assessed non-invasively by coronary computed tomography angiography (CCTA). Despite progress in automated CCTA analysis using deep learning, clinical translation is constrained by the scarcity of expert-annotated datasets. Furthermore, widely adopted label-free pretraining strategies, such as masked image modeling, are intrinsically biased toward global anatomical statistics, frequently failing to capture the spatially localized pathological features of coronary plaques. Here, we introduce CORA, a 3D vision foundation model for comprehensive cardiovascular risk assessment. CORA learns directly from volumetric CCTA via a pathology-centric, synthesis-driven self-supervised framework. By utilizing an anatomy-guided lesion synthesis engine, the model is explicitly trained to detect simulated vascular abnormalities, biasing representation learning toward clinically relevant disease features rather than dominant background anatomy. We trained CORA on a large-scale cohort of 12,801 unlabeled CCTA volumes and comprehensively evaluated the model across multi-center datasets from nine independent hospitals. Across diagnostic and anatomical tasks, including plaque characterization, stenosis detection, and coronary artery segmentation, CORA consistently outperformed the state-of-the-art 3D vision foundation models, achieving up to a 29\% performance gain. Crucially, by coupling the imaging encoder with a large language model, we extended CORA into a multimodal framework that significantly improved 30-day major adverse cardiac event (MACE) risk stratification. Our results establish CORA as a scalable and extensible foundation for unified anatomical assessment and cardiovascular risk prediction.
  </details>
