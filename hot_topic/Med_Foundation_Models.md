# 🔍 Med_Foundation_Models Papers · 2026-08-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[A Multimodal Foundation Model for Longitudinal Patient Representation and Scalable Insight Generation in Oncology](https://arxiv.org/abs/2608.24688)**  `arXiv:2608.24688`  `cs.LG`  
  _Eugene Vorontsov, Yi Kan Wang, Alican Bozkurt, Adam Casson, Ludmila Tydlitatova, Michal Zelechowski, et al._
  <details open><summary>Abstract</summary>
  Precision oncology necessitates a longitudinal model of patient state that captures cancer evolution and treatment over time, integrating multimodal observations. We introduce the oFM, a foundation model developed on a real-world oncology cohort of 1.67 million cancer patients that integrates clinical trajectories with DNA, RNA, and H&E pathology. Patient-level partitions were reserved for training, validation, and testing, with over one million patients used for training. The oFM encodes daily clinical and molecular episodes and, along with pathology images, integrates them over time to produce a patient state embedding. We evaluate frozen oFM embeddings against expert-curated clinical and molecular baseline features. In prognostic benchmarks, the oFM improved AUC for treatment response, progression-free survival, and overall survival (0.774 vs. 0.563 for overall survival). Across 11 comparative-treatment cohorts, the oFM embeddings achieved a three-fold higher pooled and scale-normalized treatment-benefit AUTOC than baseline features with improved benefit ranking in 9 of 11 cohorts, and provided stronger prognostic discrimination within both treatment arms. We also evaluated a mechanism discovery framework that interprets downstream models built on oFM embeddings by linking their predicted outcomes to clinically and biologically grounded mechanisms through an evidence-grounded temporal graph, enabling evaluation in clinical and drug-development applications.
  </details>
