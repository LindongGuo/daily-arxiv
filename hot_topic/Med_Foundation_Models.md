# 🔍 Med_Foundation_Models Papers · 2026-06-16

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Predicting Immune Biomarkers with MultiModal Mixture-of-Expert Pathology Foundation Models Empowers Precision Oncology](https://arxiv.org/abs/2606.18123)**  `arXiv:2606.18123`  `cs.CV`  
  _Tianyu Liu, Ziqing Wang, Zhaokang Liang, Tong Ding, Peter Humphrey, Lorraine Colón-Cartagena, et al._
  <details open><summary>Abstract</summary>
  Predicting immune biomarkers associated with the tumor immune microenvironment (TIME) is critical for advancing precision oncology, yet existing approaches are largely limited to single image modalities and suffer from insufficient resolution and incomplete utilization of complementary clinical and biological information. Here we introduce MixTIME, a multimodal foundation model that leverages a mixture-of-experts (MoE) architecture to integrate pathology foundation models trained across distinct modalities: image only (UNIv2), image text (CONCHv1.5), and image transcriptomic (STPath) representations for pixel-level and slide-level prediction of multiplex immunofluorescence (mIF) protein expression from hematoxylin and eosin (HE) whole-slide images. MixTIME employs a learnable router to dynamically weight expert contributions and is trained with a distribution- and tendency-aware loss function. Benchmarked on two datasets of different scales, MixTIME achieves state-of-the-art performance across 17 protein markers as measured by correlation metrics. The predicted mIF profiles substantially enhance downstream tasks, including spatial domain identification, survival prediction, and AI-assisted pathology report generation validated by expert pathologists from multiple institutes across the world. Furthermore, MixTIME enables longitudinal tracking of protein expression dynamics across clinical time points and reveals protein gene interaction patterns linked to drug resistance and immune suppression in tumor microenvironments. Collectively, MixTIME provides a scalable framework for multimodal biomarker discovery and clinical translation in computational pathology.
  </details>
