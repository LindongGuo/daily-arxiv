# 🔍 Prognosis_Survival Papers · 2026-04-22

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[AnatomicalNets: A Multi-Structure Segmentation and Contour-Based Distance Estimation Pipeline for Clinically Grounded Lung Cancer T-Staging](https://arxiv.org/abs/2511.19367)**  `arXiv:2511.19367`  `cs.CV` `cs.AI`  
  _Saniah Kayenat Chowdhury, Rusab Sarmun, Muhammad E. H. Chowdhury, Sohaib Bassam Zoghoul, Israa Al-Hashimi, Adam Mushtak, et al._
  <details open><summary>Abstract</summary>
  Accurate tumor staging in lung cancer is crucial for prognosis and treatment planning and is governed by explicit anatomical criteria under fixed guidelines. However, most existing deep learning approaches treat this spatially structured clinical decision as an uninterpretable image classification problem. Tumor stage depends on predetermined quantitative criteria, including the tumor's dimensions and its proximity to adjacent anatomical structures, and small variations can alter the staging outcome. To address this gap, we propose AnatomicalNets, a medically grounded, multi-stage pipeline that reformulates tumor staging as a measurement and rule-based inference problem rather than a learned mapping. We employ three dedicated encoder-decoder networks to precisely segment the lung parenchyma, tumor, and mediastinum. The diaphragm boundary is estimated via a lung-contour heuristic, while the tumor's largest dimension and its proximity to adjacent structures are computed through a contour-based distance estimation method. These features are passed through a deterministic decision module following the international association for the study of lung cancer guidelines. Evaluated on the Lung-PET-CT-Dx dataset, AnatomicalNets achieves an overall classification accuracy of 91.36%. We report the per-stage F1-scores of 0.93 (T1), 0.89 (T2), 0.96 (T3), and 0.90 (T4), a critical evaluation aspect often omitted in prior literature. We highlight that the representational bottleneck in prior work lies in feature design rather than classifier capacity. This work establishes a transparent and reliable staging paradigm that bridges the gap between deep learning performance and clinical interpretability.
  </details>
