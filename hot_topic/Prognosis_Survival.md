# 🔍 Prognosis_Survival Papers · 2026-06-22

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Predicting High-Risk Colorectal Polyps in African Americans Using Pre-Colonoscopy Clinical Features: Machine Learning Model Development and Temporal Validation](https://arxiv.org/abs/2606.21492)**  `arXiv:2606.21492`  `cs.LG` `cs.AI`  
  _Basheer Qolomany, Mrinalini Deverapall, Adeyinka Laiyemo, Zaki Sherif, Mori Yuichi, Omer Ahmed, et al._
  <details open><summary>Abstract</summary>
  Risk stratification for advanced colorectal polyps typically relies on colonoscopy and/or pathology findings. However, there is growing interest in whether non-invasive features available prior to colonoscopy can help identify patients at higher risk. Such approaches may enhance clinical decision-making by prioritizing surveillance for individuals most likely to harbor high-risk polyps, when colonoscopy resources are limited while potentially reducing unnecessary procedures in lower-risk patients. Importantly, the use of non-invasive, pre-procedural information may also help promote more equitable access to risk stratification, particularly in settings where colonoscopy resources are limited or unevenly distributed. We aimed to develop and externally validate machine learning models to predict high-risk colorectal polyps using only non-invasive, pre-colonoscopy demographic, clinical, and behavioral features in a diverse, predominantly African American, urban cohort.We conducted a retrospective cohort study using demographic, lifestyle, and comorbidity data from patients who underwent colonoscopy at Howard University Hospital to develop and validate several machine learning models, including neural networks, random forest, support vector machines (SVM), Naive Bayes, logistic regression, decision trees, k-nearest neighbors (KNN), and XGBoost, for predicting high-risk colorectal polyps. High-risk polyps (HRP) were defined as villous or tubullovillous adenomas, high-grade dysplasia, polyps >= 10 mm in size, and/or the presence of >= 3 polyps per procedure; all other cases were classified as low-risk polyps (LRP). The dataset included 4,681 patients from 2015-2022 used for internal validation and 1,562 patients from 2023-2024 used for external validation.
  </details>

- **[Evidential Fusion Network for Multimodal Survival Prediction under Missing Modalities](https://arxiv.org/abs/2606.20757)**  `arXiv:2606.20757`  `cs.LG`  
  _Yucheng Xing, Hailan Mo, Zi Wang, Ling Huang, Mengling Feng_
  <details open><summary>Abstract</summary>
  Recent multimodal survival prediction models have demonstrated strong predictive performance by leveraging complementary information across modalities. However, such models generally assume data completeness and exhibit limited robustness toward missing modalities, which are frequently encountered in real-world clinical settings. We propose the Evidential Missing Modality Survival Fusion (EMMS) model for multimodal survival prediction under missing modalities. EMMS offers a straightforward, computationally effective approach to survival analysis without requiring a generative phase for missing data. By employing Dempster-Shafer theory and Gaussian Random Fuzzy Numbers for multimodal decision fusion, it considers both aleatoric and epistemic uncertainty alongside modality reliability for fusion. Moreover, the model treats missing modalities as vacuous evidence, preventing interference with available inputs and naturally reflecting increased uncertainty and calibrated predictions. Extensive experiments on four cancer datasets demonstrate state-of-the-art performance while providing calibrated and interpretable uncertainty estimates under incomplete multimodal observations, without introducing additional computational overhead.
  </details>

- **[Predicting Immune Biomarkers with MultiModal Mixture-of-Expert Pathology Foundation Models Empowers Precision Oncology](https://arxiv.org/abs/2606.18123)**  `arXiv:2606.18123`  `cs.CV`  
  _Tianyu Liu, Ziqing Wang, Zhaokang Liang, Tong Ding, Peter Humphrey, Lorraine Colón-Cartagena, et al._
  <details open><summary>Abstract</summary>
  Predicting immune biomarkers associated with the tumor immune microenvironment (TIME) is critical for advancing precision oncology, yet existing approaches are largely limited to single image modalities and suffer from insufficient resolution and incomplete utilization of complementary clinical and biological information. Here we introduce MixTIME, a multimodal foundation model that leverages a mixture-of-experts (MoE) architecture to integrate pathology foundation models trained across distinct modalities: image only (UNIv2), image text (CONCHv1.5), and image transcriptomic (STPath) representations for pixel-level and slide-level prediction of multiplex immunofluorescence (mIF) protein expression from hematoxylin and eosin (HE) whole-slide images. MixTIME employs a learnable router to dynamically weight expert contributions and is trained with a distribution- and tendency-aware loss function. Benchmarked on two datasets of different scales, MixTIME achieves state-of-the-art performance across 17 protein markers as measured by correlation metrics. The predicted mIF profiles substantially enhance downstream tasks, including spatial domain identification, survival prediction, and AI-assisted pathology report generation validated by expert pathologists from multiple institutes across the world. Furthermore, MixTIME enables longitudinal tracking of protein expression dynamics across clinical time points and reveals protein gene interaction patterns linked to drug resistance and immune suppression in tumor microenvironments. Collectively, MixTIME provides a scalable framework for multimodal biomarker discovery and clinical translation in computational pathology.
  </details>
