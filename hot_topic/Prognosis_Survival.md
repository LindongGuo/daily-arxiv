# 🔍 Prognosis_Survival Papers · 2026-03-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[An Automated Radiomics Framework for Postoperative Survival Prediction in Colorectal Liver Metastases using Preoperative MRI](https://arxiv.org/abs/2603.10216)**  `arXiv:2603.10216`  `cs.CV`  
  _Muhammad Alberb, Jianan Chen, Hossam El-rewaidy, Paul Karanicolas, Arun Seth, Yutaka Amemiya, et al._
  <details open><summary>Abstract</summary>
  While colorectal liver metastasis (CRLM) is potentially curable via hepatectomy, patient outcomes remain highly heterogeneous. Postoperative survival prediction is necessary to avoid non-beneficial surgeries and guide personalized therapy. In this study, we present an automated AI-based framework for postoperative CRLM survival prediction using pre- and post-contrast MRI. We performed a retrospective study of 227 CRLM patients who had gadoxetate-enhanced MRI prior to curative-intent hepatectomy between 2013 and 2020. We developed a survival prediction framework comprising an anatomy-aware segmentation pipeline followed by a radiomics pipeline. The segmentation pipeline learns liver, CRLMs, and spleen segmentation from partially-annotated data, leveraging promptable foundation models to generate pseudo-labels. To support this pipeline, we propose SAMONAI, a prompt propagation algorithm that extends Segment Anything Model to 3D point-based segmentation. Predicted pre- and post-contrast segmentations are then fed into our radiomics pipeline, which extracts per-tumor features and predicts survival using SurvAMINN, an autoencoder-based multiple instance neural network for time-to-event survival prediction. SurvAMINN jointly learns dimensionality reduction and survival prediction from right-censored data, emphasizing high-risk metastases. We compared our framework against established methods and biomarkers using univariate and multivariate Cox regression. Our segmentation pipeline achieves median Dice scores of 0.96 (liver) and 0.93 (spleen), driving a CRLM segmentation Dice score of 0.78 and a detection F1-score of 0.79. Accurate segmentation enables our radiomics pipeline to achieve a survival prediction C-index of 0.69. Our results show the potential of integrating segmentation algorithms with radiomics-based survival analysis to deliver accurate and automated CRLM outcome prediction.
  </details>
