# 🔍 Med_Foundation_Models Papers · 2026-03-04

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[RANGER: Sparsely-Gated Mixture-of-Experts with Adaptive Retrieval Re-ranking for Pathology Report Generation](https://arxiv.org/abs/2603.04348)**  `arXiv:2603.04348`  `cs.CV` `cs.AI`  
  _Yixin Chen, Ziyu Su, Hikmat Khan, Muhammad Khalid Khan Niazi_
  <details open><summary>Abstract</summary>
  Pathology report generation remains a relatively under-explored downstream task, primarily due to the gigapixel scale and complex morphological heterogeneity of Whole Slide Images (WSIs). Existing pathology report generation frameworks typically employ transformer architectures, relying on a homogeneous decoder architecture and static knowledge retrieval integration. Such architectures limit generative specialization and may introduce noisy external guidance during the report generation process. To address these limitations, we propose RANGER, a sparsely-gated Mixture-of-Experts (MoE) framework with adaptive retrieval re-ranking for pathology report generation. Specifically, we integrate a sparsely gated MoE into the decoder, along with noisy top-$k$ routing and load-balancing regularization, to enable dynamic expert specialization across various diagnostic patterns. Additionally, we introduce an adaptive retrieval re-ranking module that selectively refines retrieved memory from a knowledge base before integration, reducing noise and improving semantic alignment based on visual feature representations. We perform extensive experiments on the PathText-BRCA dataset and demonstrate consistent improvements over existing approaches across standard natural language generation metrics. Our full RANGER model achieves optimal performance on PathText dataset, reaching BLEU-1 to BLEU-4 scores of 0.4598, 0.3044, 0.2036, and 0.1435, respectively, with METEOR of 0.1883, and ROUGE-L of 0.3038, validating the effectiveness of dynamic expert routing and adaptive knowledge refinement for semantically grounded pathology report generation.
  </details>

- **[MoECLIP: Patch-Specialized Experts for Zero-shot Anomaly Detection](https://arxiv.org/abs/2603.03101)**  `arXiv:2603.03101`  `cs.CV` `cs.AI`  
  _Jun Yeong Park, JunYoung Seo, Minji Kang, Yu Rang Park_
  <details open><summary>Abstract</summary>
  The CLIP model's outstanding generalization has driven recent success in Zero-Shot Anomaly Detection (ZSAD) for detecting anomalies in unseen categories. The core challenge in ZSAD is to specialize the model for anomaly detection tasks while preserving CLIP's powerful generalization capability. Existing approaches attempting to solve this challenge share the fundamental limitation of a patch-agnostic design that processes all patches monolithically without regard for their unique characteristics. To address this limitation, we propose MoECLIP, a Mixture-of-Experts (MoE) architecture for the ZSAD task, which achieves patch-level adaptation by dynamically routing each image patch to a specialized Low-Rank Adaptation (LoRA) expert based on its unique characteristics. Furthermore, to prevent functional redundancy among the LoRA experts, we introduce (1) Frozen Orthogonal Feature Separation (FOFS), which orthogonally separates the input feature space to force experts to focus on distinct information, and (2) a simplex equiangular tight frame (ETF) loss to regulate the expert outputs to form maximally equiangular representations. Comprehensive experimental results across 14 benchmark datasets spanning industrial and medical domains demonstrate that MoECLIP outperforms existing state-of-the-art methods. The code is available atthis https URL.
  </details>

- **[DeNuC: Decoupling Nuclei Detection and Classification in Histopathology](https://arxiv.org/abs/2603.04240)**  `arXiv:2603.04240`  `cs.CV`  
  _Zijiang Yang, Chen Kuang, Dongmei Fu_
  <details open><summary>Abstract</summary>
  Pathology Foundation Models (FMs) have shown strong performance across a wide range of pathology image representation and diagnostic tasks. However, FMs do not exhibit the expected performance advantage over traditional specialized models in Nuclei Detection and Classification (NDC). In this work, we reveal that jointly optimizing nuclei detection and classification leads to severe representation degradation in FMs. Moreover, we identify that the substantial intrinsic disparity in task difficulty between nuclei detection and nuclei classification renders joint NDC optimization unnecessarily computationally burdensome for the detection stage. To address these challenges, we propose DeNuC, a simple yet effective method designed to break through existing bottlenecks by Decoupling Nuclei detection and Classification. DeNuC employs a lightweight model for accurate nuclei localization, subsequently leveraging a pathology FM to encode input images and query nucleus-specific features based on the detected coordinates for classification. Extensive experiments on three widely used benchmarks demonstrate that DeNuC effectively unlocks the representational potential of FMs for NDC and significantly outperforms state-of-the-art methods. Notably, DeNuC improves F1 scores by 4.2% and 3.6% (or higher) on the BRCAM2C and PUMA datasets, respectively, while using only 16% (or fewer) trainable parameters compared to other methods. Code is available atthis https URL.
  </details>
