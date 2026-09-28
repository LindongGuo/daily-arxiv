# 🔍 Med_Foundation_Models Papers · 2026-09-27

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[FedHisto-PAST: Parameter-Efficient Stain-Aware Federated Learning for Cross-Site Lung Histopathology Classification](https://arxiv.org/abs/2609.31150)**  `arXiv:2609.31150`  `cs.CV` `cs.AI`  
  _Muhammad Muhtasim Shahriar, M. M. Golam Hafiz, Saad Aloteibi, Mohammad Ali Moni_
  <details open><summary>Abstract</summary>
  Cross-site lung histopathology classification must account for stain variation, non-IID client data, missing classes, and the cost of adapting large pathology encoders. This study evaluates FedHisto-PAST v2 for three-way classification of adenocarcinoma (ACA), Normal, and squamous cell carcinoma (SCC). FedHisto-PAST v2 combines a frozen HIBOU-B foundation model with parameter-efficient adaptation, stain-conditioned paired-view prediction and feature consistency, reliability-aware prototype learning, and adaptive federated aggregation. Experiments used a five-client, non-IID, raw-data-local simulation with fixed internal evaluation, client-level analysis, component ablations, communication accounting, and a development-influenced exploratory LungHist700 cohort. All principal methods achieved near- ceiling internal performance, which limited discrimination on the fixed split. On LungHist700, FedHisto- PAST v2 achieved a Macro-F1 of 0.728560 and a balanced accuracy of 0.730454. Higher recognition of Normal and SCC was accompanied by lower ACA recall, and calibration remained imperfect. Prediction-level consistency was the only component with a clearly supported independent contribution in the external ablation analysis. Feature consistency and prototype regularization showed no conclusive independent overall gains in Macro-F1. The framework updated 1.253841% of the model parameters. The results provide exploratory cross-dataset evidence for stain-aware, parameter-efficient federation; they do not establish formal privacy, patient-level independence, prospective deployment, or clinical validation.
  </details>
