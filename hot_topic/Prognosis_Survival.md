# 🔍 Prognosis_Survival Papers · 2026-04-27

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[A Digital Pathology Resource for Liver Cancer Quantification with Datasets, Benchmarks, and Tools](https://arxiv.org/abs/2604.22858)**  `arXiv:2604.22858`  `cs.CV`  
  _Ying Xiao, Shimiao Tang, Xitong Ling, Weiming Chen, Jun Wang, Jiawen Li, et al._
  <details open><summary>Abstract</summary>
  Liver cancer, especially hepatocellular carcinoma (HCC), imposes a substantial global disease burden. Accurate diagnosis and prognostic assessment directly influence treatment selection and patient survival, and pathological examination remains the gold standard for liver cancer diagnosis. Identifying diverse tissue components and pathological subtypes on histopathology slides is crucial for estimating postoperative recurrence risk and overall prognosis. However, most publicly available resources are still provided at the whole-slide image (WSI) level, and well-annotated datasets for fine-grained tissue component identification in liver cancer are scarce, which hinders reproducible model development and the deployment of quantitative analysis tools. To address this gap, we release HepatoBench, a patch-level image database for liver cancer with annotations for seven key tissue categories. Based on HepatoBench, we train and open-source a deep learning classification model as a tissue recognition tool. Furthermore, we train a WSI-level tumor/non-tumor segmentation model to automatically localize lesion regions across entire slides. By integrating the patch-level tissue classifier with the WSI-level segmentation model, we build HepatoQuant, an end-to-end, disease-specific regional quantification tool for liver cancer, enabling a unified workflow from WSIs to tissue composition parsing and quantitative statistics. We also open-source HepatoBench, the benchmarking protocol, and supporting tools, providing a solid foundation for automated regional quantification and fair method comparison in liver cancer pathology.
  </details>
