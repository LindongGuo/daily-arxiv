# 🔍 ST_Generation_Imputation Papers · 2026-03-20

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[CytoSyn: a Foundation Diffusion Model for Histopathology -- Tech Report](https://arxiv.org/abs/2603.18089)**  `arXiv:2603.18089`  `cs.CV` `cs.AI` `cs.LG`  
  _Thomas Duboudin, Xavier Fontaine, Etienne Andrier, Lionel Guillou, Alexandre Filiot, Thalyssa Baiocco-Rodrigues, et al._
  <details open><summary>Abstract</summary>
  Computational pathology has made significant progress in recent years, fueling advances in both fundamental disease understanding and clinically ready tools. This evolution is driven by the availability of large amounts of digitized slides and specialized deep learning methods and models. Multiple self-supervised foundation feature extractors have been developed, enabling downstream predictive applications from cell segmentation to tumor sub-typing and survival analysis. In contrast, generative foundation models designed specifically for histopathology remain scarce. Such models could address tasks that are beyond the capabilities of feature extractors, such as virtual staining. In this paper, we introduce CytoSyn, a state-of-the-art foundation latent diffusion model that enables the guided generation of highly realistic and diverse histopathology H&E-stained images, as shown in an extensive benchmark. We explored methodological improvements, training set scaling, sampling strategies and slide-level overfitting, culminating in the improved CytoSyn-v2, and compared our work to PixCell, a state-of-the-art model, in an in-depth manner. This comparison highlighted the strong sensitivity of both diffusion models and performance metrics to preprocessing-specific details such as JPEG compression. Our model has been trained on a dataset obtained from more than 10,000 TCGA diagnostic whole-slide images of 32 different cancer types. Despite being trained only on oncology slides, it maintains state-of-the-art performance generating inflammatory bowel disease images. To support the research community, we publicly release CytoSyn's weights, its training and validation datasets, and a sample of synthetic images in this repository:this https URL.
  </details>

- **[Translating MRI to PET through Conditional Diffusion Models with Enhanced Pathology Awareness](https://arxiv.org/abs/2603.18896)**  `arXiv:2603.18896`  `cs.CV` `cs.AI`  
  _Yitong Li, Igor Yakushev, Dennis M. Hedderich, Christian Wachinger_
  <details open><summary>Abstract</summary>
  Positron emission tomography (PET) is a widely recognized technique for diagnosing neurodegenerative diseases, offering critical functional insights. However, its high costs and radiation exposure hinder its widespread use. In contrast, magnetic resonance imaging (MRI) does not involve such limitations. While MRI also detects neurodegenerative changes, it is less sensitive for diagnosis compared to PET. To overcome such limitations, one approach is to generate synthetic PET from MRI. Recent advances in generative models have paved the way for cross-modality medical image translation; however, existing methods largely emphasize structural preservation while neglecting the critical need for pathology awareness. To address this gap, we propose PASTA, a novel image translation framework built on conditional diffusion models with enhanced pathology awareness. PASTA surpasses state-of-the-art methods by preserving both structural and pathological details through its highly interactive dual-arm architecture and multi-modal condition integration. Additionally, we introduce a novel cycle exchange consistency and volumetric generation strategy that significantly enhances PASTA's ability to produce high-quality 3D PET images. Our qualitative and quantitative results demonstrate the high quality and pathology awareness of the synthesized PET scans. For Alzheimer's diagnosis, the performance of these synthesized scans improves over MRI by 4%, almost reaching the performance of actual PET. Our code is available atthis https URL.
  </details>

- **[Cell-Type Prototype-Informed Neural Network for Gene Expression Estimation from Pathology Images](https://arxiv.org/abs/2603.18461)**  `arXiv:2603.18461`  `cs.CV`  
  _Kazuya Nishimura, Ryoma Bise, Shinnosuke Matsuo, Haruka Hirose, Yasuhiro Kojima_
  <details open><summary>Abstract</summary>
  Estimating slide- and patch-level gene expression profiles from pathology images enables rapid and low-cost molecular analysis with broad clinical impact. Despite strong results, existing approaches treat gene expression as a mere slide- or spot-level signal and do not incorporate the fact that the measured expression arises from the aggregation of underlying cell-level expression. To explicitly introduce this missing cell-resolved guidance, we propose a Cell-type Prototype-informed Neural Network (CPNN) that leverages publicly available single-cell RNA-sequencing datasets. Since single-cell measurements are noisy and not paired with histology images, we first estimate cell-type prototypes-mean expression profiles that reflect stable gene-gene co-variationthis http URLthen learns cell-type compositional weights directly from images and models the relationship between prototypes and observed bulk or spatial expression, providing a biologically grounded and structurally regularized prediction framework. We evaluate CPNN on three slide-level datasets and three patch-level spatial transcriptomics datasets. Across all settings, CPNN achieves the highest performance in terms of Spearman correlation. Moreover, by visualizing the inferred compositional weights, our framework provides interpretable insights into which cell types drive the predicted expression. Code is publicly available atthis https URL.
  </details>
