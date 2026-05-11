# 🔍 Med_Foundation_Models Papers · 2026-05-10

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Radiologist-Guided Causal Concept Bottleneck Models for Chest X-Ray Interpretation](https://arxiv.org/abs/2605.07785)**  `arXiv:2605.07785`  `cs.CV`  
  _Amy Rafferty, Rishi Ramaesh, Ajitha Rajan_
  <details open><summary>Abstract</summary>
  Concept Bottleneck Models (CBMs) in medical imaging aim to improve model interpretability by predicting intermediate clinical concepts before final diagnoses. However, most existing CBMs treat concepts as discriminative predictors of pathology labels, without explicitly modelling the underlying clinical generative process where diseases produce observable radiographic findings. We propose XpertCausal, a radiologist-guided causal CBM for chest X-ray interpretation which models pathology-to-concept relationships using a probabilistic noisy-OR framework. This generative model is then inverted via Bayesian inference to estimate pathology probabilities from predicted concepts. Radiologist-curated concept-pathology associations are used to constrain model structure to radiologist-defined clinically plausible reasoning pathways. We evaluate XpertCausal on MIMIC-CXR across pathology classification performance, calibration, explanation quality, and alignment with radiologist-defined reasoning pathways. Compared with both a non-causal CBM baseline and a causal ablation with unconstrained learned associations, XpertCausal achieves improved AUROC, calibration, and clinically relevant explanation quality, while learning concept-pathology relationships that more closely align with expert knowledge. These results demonstrate that incorporating clinically motivated causal structure and expert domain knowledge into CBMs can lead to more accurate, interpretable, and clinically aligned models for CXR interpretation.
  </details>
