# 🔍 Prognosis_Survival Papers · 2026-09-21

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Preoperative Prediction of Microvascular Invasion in Hepatocellular Carcinoma by Integrating Multimodal Ultrasound and Clinical Data: A Multicenter Study](https://arxiv.org/abs/2609.24524)**  `arXiv:2609.24524`  `cs.CV`  
  _Jun Cheng, Yuanyuan Kong, Qing Huang, Xiaotong Tan, Licong Dong, Yulong Han, et al._
  <details open><summary>Abstract</summary>
  Background: Microvascular invasion (MVI) predicts recurrence and survival in hepatocellular carcinoma (HCC) but requires postoperative histopathology for diagnosis. We developed and validated a model integrating multimodal ultrasound and clinical data for preoperative MVI prediction. Methods: This multicenter study included 489 patients with HCC from eight centers. All patients had B-mode ultrasound (BUS), color Doppler flow imaging (CDFI), dynamic contrast-enhanced ultrasound (DCE-US), and clinical information. Data from seven centers (n = 421) were used for model development with five-fold cross-validation; data from the remaining center (n = 68) formed an independent external validation cohort. The proposed multimodal information fusion network used modality-specific encoders, a hemodynamic temporal change module for bidirectional DCE-US perfusion changes, and a representation consistency learning module to align heterogeneous ultrasound representations before Transformer-based fusion. Results: In external validation, DCE-US achieved the highest single-modality area under the receiver operating characteristic curve (AUC; 0.8545+/-0.0198), versus clinical information (0.6715+/-0.0156), CDFI (0.6435+/-0.0344), and BUS (0.6087+/-0.0417). Pixel-difference sampling and the proposed temporal module outperformed alternative sampling and video representation methods. The full model achieved the best performance, with an AUC of 0.8953+/-0.0180, accuracy of 81.18%+/-2.83%, sensitivity of 86.40%+/-6.69%, and specificity of 78.14%+/-6.28. Conclusions: Integrating multimodal ultrasound and clinical information enabled promising preoperative MVI prediction in HCC. DCE-US was the main source of predictive information, while BUS, CDFI, and clinical information provided complementary value. The proposed framework may support preoperative risk stratification and individualized clinical decision-making.
  </details>
