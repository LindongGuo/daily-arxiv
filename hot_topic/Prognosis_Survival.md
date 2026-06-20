# 🔍 Prognosis_Survival Papers · 2026-06-19

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Semantic-Anchored Evidential Fusion for Domain-Robust Whole-Slide Survival Analysis](https://arxiv.org/abs/2606.19966)**  `arXiv:2606.19966`  `cs.CV` `cs.LG`  
  _Yucheng Xing, Ling Huang, Pei Liu, Jingying Ma, Jiaqing Xu, Kai He, et al._
  <details open><summary>Abstract</summary>
  Whole-slide images (WSIs) are widely used for computational cancer prognosis. However, most existing methods primarily focus on in-domain performance and fail to generalize across clinical centers. This limitation stems from their reliance on pixel-derived representations that are highly susceptible to domain-specific artifacts caused by staining protocols and scanner hardware. We hypothesize that high-level pathology semantics, such as tumor grade and micro-environmental architecture, provide a domain-invariant semantic representation that mirrors the robust diagnostic logic of human pathologists. Therefore, we propose a Semantic-Anchored Evidential Fusion Survival (SAEFS) framework, where SAEFS derives semantic anchors from WSIs via Visual Question Answering (VQA), employs a dual-stream WSI evidence extraction architecture, uses Dirichlet-based Subjective Logic to model uncertainty, and fuses semantic and visual evidence through a cautious conjunction rule to avoid overconfident fusion from correlated sources. Trained exclusively on one source domain and evaluated zero-shot across four unseen domains, SAEFS consistently outperforms state-of-the-art models both in prediction accuracy and reliability, improving the average C-index by 10.2%. Quantitative analyses further show that VQA-derived semantic features exhibit significantly lower cross-center divergence than pixel-derived features, highlighting their robustness for cross-center clinical applications.
  </details>

- **[HEad and neCK TumOR (HECKTOR) 2025: Benchmark of Segmentation, Diagnosis, and Prognosis in Multimodal PET/CT](https://arxiv.org/abs/2606.20143)**  `arXiv:2606.20143`  `cs.CV`  
  _Numan Saeed, Salma Hassan, Shahad Hardan, Lishan Cai, Xinglong Liang, Moona Mazher, et al._
  <details open><summary>Abstract</summary>
  Head and neck cancers (HNC) represent a significant global health burden, with accurate tumor delineation being essential for effective radiotherapy planning. The complexity of the oropharyngeal anatomy, combined with the heterogeneous appearance of tumors on imaging, makes manual segmentation time-intensive and subject to inter-observer variability. Beyond segmentation, predicting long-term clinical outcomes, such as recurrence-free survival (RFS), and determining human papillomavirus (HPV) status from noninvasive imaging, remain challenging yet clinically valuable goals. The HECKTOR 2025 challenge addresses these needs by establishing a comprehensive benchmark for automated HNC analysis using multimodal PET/CT imaging and electronic health records. Building on previous editions (2020-2022), this challenge features an expanded multi-institutional dataset comprising over 1,100 patients from 10 centers worldwide. Participants were tasked with three complementary objectives: (1) segmenting primary gross tumor volumes (GTVp) and metastatic lymph nodes (GTVn), (2) predicting recurrence-free survival, and (3) classifying HPV status. The challenge attracted 35 registered teams, with 15 final submissions evaluated on a held-out test set. Top-performing algorithms achieved a mean Dice similarity coefficient of 0.75 for segmentation, a concordance index of 0.66 for survival prediction, and a balanced accuracy of 0.56 for HPV classification. This paper presents a comprehensive analysis of the submitted methodologies, evaluates their performance across different lesion characteristics, and discusses their implications for clinical translation in automated oncology workflows and decision support systems.
  </details>
