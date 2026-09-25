# 🔍 Med_Foundation_Models Papers · 2026-09-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[A Multimodal 3D Foundation Model for Light Sheet Fluorescence Microscopy Enables Few-Shot Segmentation, Classification, and Deblurring](https://arxiv.org/abs/2605.26026)**  `arXiv:2605.26026`  `cs.CV` `cs.AI` `cs.LG`  
  _Adina Scheinfeld, Haotan Zhang, Shang Mu, Rudolf L. M. van Herten, Lucas Stoffl, Ali Erturk, et al._
  <details open><summary>Abstract</summary>
  Light sheet fluorescence microscopy (LSM) enables high-resolution, three-dimensional (3D) imaging of biological specimens, providing rich volumetric data for studying cellular organization, pathology, and vascular networks. However, the size, dimensionality, and annotation burden of LSM data make supervised deep learning approaches costly and difficult to scale. Additionally, despite the abundance of unannotated LSM volumes, foundation models for this modality remain underexplored due to computational challenges and the complexity of volumetric representation learning. In this work, we introduce a 3D foundation model for LSM data, pretrained on a large curated collection of 3D images spanning multiple organisms, stains, and imaging protocols. We learn transferable volumetric representations by jointly optimizing for masked reconstruction and image-text alignment. The pretrained backbone drastically reduces the annotation burden, enabling efficient, few-shot adaptation for varied downstream tasks. We evaluate this approach on downstream segmentation, classification, and deblurring. Our results demonstrate consistent improvements over baselines, (1) when measured using standard evaluation metrics and (2) when rigorously assessed by domain experts. This highlights the potential of foundation model pretraining to reduce annotation requirements while improving performance across diverse LSM analysis tasks. Pretrained model weights and code for pretraining and finetuning are publicly available:this https URL.
  </details>

- **[Cross-Task Generalization in Handwriting-Based Alzheimer's Screening via Vision Language Adaptation](https://arxiv.org/abs/2511.05841)**  `arXiv:2511.05841`  `cs.CV` `cs.AI`  
  _Changqing Gong, Huafeng Qin, Mounim A. El-Yacoubi_
  <details open><summary>Abstract</summary>
  Alzheimer's disease (AD) is a prevalent neurodegenerative disorder for which early detection is critical. Handwriting, which can be disrupted by subtle motor and cognitive decline, provides a non-invasive and cost-effective window for AD screening. Existing handwriting-based AD studies mostly rely on online trajectories and hand-crafted features, while the influence of handwriting task type on diagnostic performance and cross-task generalization remains underexplored. Meanwhile, large-scale vision--language models have demonstrated strong transfer and adaptation ability in natural-image anomaly detection and several medical modalities, such as chest X-ray and brain MRI. However, handwriting-based disease detection remains unexplored within this paradigm. To address this gap, we introduce a lightweight Cross-Layer Fusion Adapter (CLFA) framework that repurposes Contrastive Language--Image Pre-training (CLIP) for handwriting-based AD screening. CLFA inserts multi-level adapters into a frozen visual encoder, combining cross-layer feature fusion with depthwise 2D convolution on patch grids to capture both local stroke irregularities and higher-level handwriting structure. This design progressively aligns pretrained vision--language representations with AD-related handwriting cues and supports transfer from supervised source tasks to task-disjoint unseen target tasks. On the Darwin dataset, under the subject-disjoint cross-task protocol, averaged over all 600 task-disjoint source-target pairs, CLFA achieves 74.63\% AUC, 74.85\% accuracy, and 73.72\% F1 score, outperforming the best competing model by 2.15, 1.79, and 1.87 percentage points, respectively.
  </details>
