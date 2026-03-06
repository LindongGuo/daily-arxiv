# 🔍 Prognosis_Survival Papers · 2026-03-05

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Comparative Evaluation of Traditional Methods and Deep Learning for Brain Glioma Imaging. Review Paper](https://arxiv.org/abs/2603.04796)**  `arXiv:2603.04796`  `cs.CV` `cs.AI`  
  _Kiranmayee Janardhan, Vinay Martin DSa Prabhu, T. Christy Bobby_
  <details open><summary>Abstract</summary>
  Segmentation is crucial for brain gliomas as it delineates the glioma s extent and location, aiding in precise treatment planning and monitoring, thus improving patient outcomes. Accurate segmentation ensures proper identification of the glioma s size and position, transforming images into applicable data for analysis. Classification of brain gliomas is also essential because different types require different treatment approaches. Accurately classifying brain gliomas by size, location, and aggressiveness is essential for personalized prognosis prediction, follow-up care, and monitoring disease progression, ensuring effective diagnosis, treatment, and management. In glioma research, irregular tissues are often observable, but error free and reproducible segmentation is challenging. Many researchers have surveyed brain glioma segmentation, proposing both fully automatic and semi-automatic techniques. The adoption of these methods by radiologists depends on ease of use and supervision, with semi-automatic techniques preferred due to the need for accurate evaluations. This review evaluates effective segmentation and classification techniques post magnetic resonance imaging acquisition, highlighting that convolutional neural network architectures outperform traditional techniques in these tasks.
  </details>

- **[CARE: A Molecular-Guided Foundation Model with Adaptive Region Modeling for Whole Slide Image Analysis](https://arxiv.org/abs/2602.21637)**  `arXiv:2602.21637`  `cs.CV`  
  _Di Zhang, Zhangpeng Gong, Xiaobo Pang, Jiashuai Liu, Junbo Lu, Hao Cui, et al._
  <details open><summary>Abstract</summary>
  Foundation models have recently achieved impressive success in computational pathology, demonstrating strong generalization across diverse histopathology tasks. However, existing models overlook the heterogeneous and non-uniform organization of pathological regions of interest (ROIs) because they rely on natural image backbones not tailored for tissue morphology. Consequently, they often fail to capture the coherent tissue architecture beyond isolated patches, limiting interpretability and clinical relevance. To address these challenges, we present Cross-modal Adaptive Region Encoder (CARE), a foundation model for pathology that automatically partitions WSIs into several morphologically relevant regions. Specifically, CARE employs a two-stage pretraining strategy: (1) a self-supervised unimodal pretraining stage that learns morphological representations from 34,277 whole-slide images (WSIs) without segmentation annotations, and (2) a cross-modal alignment stage that leverages RNA and protein profiles to refine the construction and representation of adaptive regions. This molecular guidance enables CARE to identify biologically relevant patterns and generate irregular yet coherent tissue regions, selecting the most representative area as ROI. CARE supports a broad range of pathology-related tasks, using either the ROI feature or the slide-level feature obtained by aggregating adaptive regions. Based on only one-tenth of the pretraining data typically used by mainstream foundation models, CARE achieves superior average performance across 33 downstream benchmarks, including morphological classification, molecular prediction, and survival analysis, and outperforms other foundation model baselines overall.
  </details>
