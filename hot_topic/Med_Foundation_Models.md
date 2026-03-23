# 🔍 Med_Foundation_Models Papers · 2026-03-22

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[On the Cone Effect and Modality Gap in Medical Vision-Language Embeddings](https://arxiv.org/abs/2603.17246)**  `arXiv:2603.17246`  `cs.LG`  
  _David Restrepo, Miguel L Martins, Chenwei Wu, Luis Filipe Nakayama, Diego M Lopez, Stergios Christodoulidis, et al._
  <details open><summary>Abstract</summary>
  Vision-Language Models (VLMs) exhibit a characteristic "cone effect" in which nonlinear encoders map embeddings into highly concentrated regions of the representation space, contributing to cross-modal separation known as the modality gap. While this phenomenon has been widely observed, its practical impact on supervised multimodal learning -- particularly in medical domains -- remains unclear. In this work, we introduce a lightweight post-hoc mechanism that keeps pretrained VLM encoders frozen while continuously controlling cross-modal separation through a single hyperparameter {\lambda}. This enables systematic analysis of how the modality gap affects downstream multimodal performance without expensive retraining. We evaluate generalist (CLIP, SigLIP) and medically specialized (BioMedCLIP, MedSigLIP) models across diverse medical and natural datasets in a supervised multimodal settings. Results consistently show that reducing excessive modality gap improves downstream performance, with medical datasets exhibiting stronger sensitivity to gap modulation; however, fully collapsing the gap is not always optimal, and intermediate, task-dependent separation yields the best results. These findings position the modality gap as a tunable property of multimodal representations rather than a quantity that should be universally minimized.
  </details>

- **[FB-CLIP: Fine-Grained Zero-Shot Anomaly Detection with Foreground-Background Disentanglement](https://arxiv.org/abs/2603.19608)**  `arXiv:2603.19608`  `cs.CV` `cs.AI`  
  _Ming Hu, Yongsheng Huo, Mingyu Dou, Jianfu Yin, Peng Zhao, Yao Wang, et al._
  <details open><summary>Abstract</summary>
  Fine-grained anomaly detection is crucial in industrial and medical applications, but labeled anomalies are often scarce, making zero-shot detection challenging. While vision-language models like CLIP offer promising solutions, they struggle with foreground-background feature entanglement and coarse textual semantics. We propose FB-CLIP, a framework that enhances anomaly localization via multi-strategy textual representations and foreground-background separation. In the textual modality, it combines End-of-Text features, global-pooled representations, and attention-weighted token features for richer semantic cues. In the visual modality, multi-view soft separation along identity, semantic, and spatial dimensions, together with background suppression, reduces interference and improves discriminability. Semantic Consistency Regularization (SCR) aligns image features with normal and abnormal textual prototypes, suppressing uncertain matches and enlarging semantic gaps. Experiments show that FB-CLIP effectively distinguishes anomalies from complex backgrounds, achieving accurate fine-grained anomaly detection and localization under zero-shot settings.
  </details>

- **[Can Large Multimodal Models Inspect Buildings? A Hierarchical Benchmark for Structural Pathology Reasoning](https://arxiv.org/abs/2603.20148)**  `arXiv:2603.20148`  `cs.CV`  
  _Hui Zhong, Yichun Gao, Luyan Liu, Hai Yang, Wang Wang, Haowei Zhang, et al._
  <details open><summary>Abstract</summary>
  Automated building facade inspection is a critical component of urban resilience and smart city maintenance. Traditionally, this field has relied on specialized discriminative models (e.g., YOLO, Mask R-CNN) that excel at pixel-level localization but are constrained to passive perception and worse generization without the visual understandng to interpret structural topology. Large Multimodal Models (LMMs) promise a paradigm shift toward active reasoning, yet their application in such high-stakes engineering domains lacks rigorous evaluation standards. To bridge this gap, we introduce a human-in-the-loop semi-automated annotation framework, leveraging expert-proposal verification to unify 12 fragmented datasets into a standardized, hierarchical ontology. Building on this foundation, we present \textit{DefectBench}, the first multi-dimensional benchmark designed to interrogate LMMs beyond basic semantic recognition. \textit{DefectBench} evaluates 18 state-of-the-art (SOTA) LMMs across three escalating cognitive dimensions: Semantic Perception, Spatial Localization, and Generative Geometry Segmentation. Extensive experiments reveal that while current LMMs demonstrate exceptional topological awareness and semantic understanding (effectively diagnosing "what" and "how"), they exhibit significant deficiencies in metric localization precision ("where"). Crucially, however, we validate the viability of zero-shot generative segmentation, showing that general-purpose foundation models can rival specialized supervised networks without domain-specific training. This work provides both a rigorous benchmarking standard and a high-quality open-source database, establishing a new baseline for the advancement of autonomous AI agents in civil engineering.
  </details>
