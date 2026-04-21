# 🔍 Prognosis_Survival Papers · 2026-04-20

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Multimodal Fusion of Histopathology Images and Electronic Health Records for Early Breast Cancer Diagnosis](https://arxiv.org/abs/2604.17122)**  `arXiv:2604.17122`  `cs.CV`  
  _Aditya Shribhagwan Khandelwal, Mohammad Samar Ansari, Asra Aslam_
  <details open><summary>Abstract</summary>
  Breast cancer is a leading cause of cancer-related mortality worldwide, and timely accurate diagnosis is critical to improving survival outcomes. While convolutional neural networks (CNNs) have demonstrated strong performance on histopathology image classification, and machine learning models on structured electronic health records (EHR) have shown utility for clinical risk stratification, most existing work treats these modalities in isolation. This paper presents a systematic multimodal framework that integrates patch-level histopathology features from the BreCaHAD dataset with structured clinical data from MIMIC-IV. We train and evaluate unimodal image models (a simple CNN baseline and ResNet-18 with transfer learning), unimodal tabular models (XGBoost and a multilayer perceptron), and an intermediate-fusion model that concatenates latent representations from both modalities. ResNet-18 achieves near-perfect accuracy (1.000) and AUC (1.000) on three-class patch-level classification, while XGBoost achieves 98% accuracy on the EHR prediction task. The intermediate fusion model yields a macro-average AUC of 0.997, outperforming all unimodal baselines and delivering the largest improvements on the diagnostically critical but class-imbalanced mitosis category (AUC 0.994). Grad-CAM and SHAP interpretability analyses validate that model decisions align with established pathological and clinical criteria. Our results demonstrate that multimodal integration delivers meaningful improvements in both predictive performance and clinical transparency.
  </details>
