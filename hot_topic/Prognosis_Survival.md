# 🔍 Prognosis_Survival Papers · 2026-05-26

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[CleanSurvival: Automated data preprocessing for time-to-event models using reinforcement learning](https://arxiv.org/abs/2502.03946)**  `arXiv:2502.03946`  `cs.LG`  
  _Yousef Koka, David Selby, Gerrit Großmann, Kathan Pandya, Sebastian Vollmer_
  <details open><summary>Abstract</summary>
  Data preprocessing is often paid little attention in machine learning, despite its potentially significant impact on model performance. While automated machine learning pipelines are starting to recognize and integrate data preprocessing into their solutions for classification and regression tasks, this integration is lacking for more specialized tasks like time-to-event models for censored data. As a result, survival analysis not only faces the general challenges of data preprocessing but also suffers from the lack of tailored, automated solutions in this area. To address this gap, this paper presents CleanSurvival, a reinforcement-learning-based solution for optimizing preprocessing pipelines, extended specifically for survival analysis. The framework can handle continuous and categorical variables. It builds upon Learn2Clean's Q-learning to select which combination of data imputation, outlier detection and feature extraction techniques achieves optimal performance for a Cox, random forest, neural network or user-supplied time-to-event model. The Python package is available on GitHub:this https URL. Experimental benchmarks on real-world datasets show that the Q-learning-based data preprocessing can improve predictive performance relative to simple baselines, while runtime behavior is condition-dependent and most clearly interpretable in the best-covered benchmark cells. Furthermore, a simulation study demonstrates effectiveness across different types and levels of missingness and noise. With an increase in the use of machine learning, it becomes important to generalise AutoML pipelines to a variety of models now present, including survival analysis. Tools like CleanSurvival, which integrate preprocessing for survival analysis, can make survival studies easier and quicker to perform, as well as make the results more robust.
  </details>

- **[BioFact-MoE: Biologically Factorized Mixture of Experts for Vision-Language Prognostic Modeling in Hepatocellular Carcinoma](https://arxiv.org/abs/2605.26376)**  `arXiv:2605.26376`  `cs.CV` `cs.AI` `cs.LG`  
  _Junlin Yang, Tian Yu, Nicha C. Dvornek, Yuexi Du, Peiyu Duan, Annabella Shewarega, et al._
  <details open><summary>Abstract</summary>
  Hepatocellular carcinoma (HCC) is biologically heterogeneous, shaped by the interplay between hepatic functional reserve and tumor-related oncologic factors; thus, similar survival outcomes may reflect fundamentally different underlying biological processes. Prognostic modeling in HCC is informed by rich multimodal information from multiparametric MRI and radiology reports from routine clinical practice. Existing prognostic vision-language models (VLMs) learn a single entangled latent representation that blends hepatic and tumor-related factors, limiting both accuracy and biological interpretability. We present BioFact-MoE, a biologically factorized Mixture of Experts (MoE) framework that explicitly decomposes liver and tumor factors via biologically supervised experts within a residual MoE survival architecture. On a HCC cohort of N=588 patients (pretrained on 4,582 3D MRI image-report pairs), BioFact-MoE consistently improves survival prediction over all baselines across time horizons, achieving 12-, 18-, and 24-month AUCs of 75.33%, 75.85%, and 73.96%. Beyond scalar risk prediction, gated expert weights enable phenotype-aware risk stratification. Pathway-informed gating uncovers clinically meaningful treatment-associated survival heterogeneity. In held-out validation, hepatic and tumor embeddings show selective associations with liver function and tumor burden markers, respectively (p<0.05), without supervision. The code is available atthis https URL.
  </details>
