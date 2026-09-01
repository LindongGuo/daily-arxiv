# 🔍 Prognosis_Survival Papers · 2026-08-31

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Towards Accurate and Lightweight Peripheral Neuroblastic Tumor Diagnosis via Contrastive Multi-scale Pathological Image Analysis](https://arxiv.org/abs/2504.13754)**  `arXiv:2504.13754`  `cs.CV` `cs.AI`  
  _Zhu Zhu, Shuo Jiang, Jingyuan Zheng, Yawen Li, Yifei Chen, Manli Zhao, et al._
  <details open><summary>Abstract</summary>
  Peripheral neuroblastic tumors (pNTs) are among the most common extracranial solid tumors in children, and accurate pathological subtyping is important for risk stratification and treatment planning. However, pNT subtyping on hematoxylin-eosin whole-slide images (WSIs) remains challenging because of limited pediatric tumor cohorts, marked histological heterogeneity, inter-observer variability, and the computational burden of existing WSI classifiers. To address these challenges, we propose CoPath, a framework consisting of CoHisNet and PathVote. CoHisNet is a lightweight multi-scale feature-fusion network for patch-level histopathological classification. By replacing the multilayer perceptron components in Swin Transformer blocks and the classification head with Kolmogorov-Arnold Network layers, CoHisNet improves nonlinear feature modeling under a compact architecture. Its multi-scale interaction and contrast-driven feature-enhancement design enables the model to capture both tissue-level structures and fine-grained cellular morphology. PathVote further incorporates pathology-informed tissue-component priors to aggregate patch-level predictions into WSI-level decisions. We validated CoPath on a private two-branch PpNTs cohort and the public BreakHis breast cancer histopathology dataset. Experimental results show that CoPath achieves competitive or superior performance compared with general image classifiers, pathology foundation models under linear probing, and pathology-specific classification models, while maintaining substantially lower computational complexity. The source code is available atthis https URL.
  </details>

- **[Multimodal Feature Prototype Learning for Interpretable and Discriminative Cancer Survival Prediction](https://arxiv.org/abs/2510.06113)**  `arXiv:2510.06113`  `cs.CV`  
  _Shuo Jiang, Zhuwen Chen, Liaoman Xu, Yanming Zhu, Changmiao Wang, Jiong Zhang, et al._
  <details open><summary>Abstract</summary>
  Survival analysis plays a vital role in making clinical decisions. However, the models currently in use are often difficult to interpret, which reduces their usefulness in clinical settings. Prototype learning presents a potential solution, yet traditional methods focus on local similarities and static matching, neglecting the broader tumor context and lacking strong semantic alignment with genomic data. To overcome these issues, we introduce an innovative prototype-based multimodal framework, FeatProto, aimed at enhancing cancer survival prediction by addressing significant limitations in current prototype learning methodologies within pathology. Our framework establishes a unified feature prototype space that integrates both global and local features of whole slide images (WSI) with genomic profiles. This integration facilitates traceable and interpretable decision-making processes. Our approach includes three main innovations: (1) A robust phenotype representation that merges critical patches with global context, harmonized with genomic data to minimize local bias. (2) An Exponential Prototype Update Strategy (EMA ProtoUp) that sustains stable cross-modal associations and employs a wandering mechanism to adapt prototypes flexibly to tumor heterogeneity. (3) A hierarchical prototype matching scheme designed to capture global centrality, local typicality, and cohort-level trends, thereby refining prototype inference. Comprehensive evaluations on four publicly available cancer datasets indicate that our method surpasses current leading unimodal and multimodal survival prediction techniques in both accuracy and interpretability, providing a new perspective on prototype learning for critical medical applications. Our source code is available atthis https URL.
  </details>
