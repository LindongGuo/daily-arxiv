# 🔍 Med_Foundation_Models Papers · 2026-08-31

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Towards Accurate and Lightweight Peripheral Neuroblastic Tumor Diagnosis via Contrastive Multi-scale Pathological Image Analysis](https://arxiv.org/abs/2504.13754)**  `arXiv:2504.13754`  `cs.CV` `cs.AI`  
  _Zhu Zhu, Shuo Jiang, Jingyuan Zheng, Yawen Li, Yifei Chen, Manli Zhao, et al._
  <details open><summary>Abstract</summary>
  Peripheral neuroblastic tumors (pNTs) are among the most common extracranial solid tumors in children, and accurate pathological subtyping is important for risk stratification and treatment planning. However, pNT subtyping on hematoxylin-eosin whole-slide images (WSIs) remains challenging because of limited pediatric tumor cohorts, marked histological heterogeneity, inter-observer variability, and the computational burden of existing WSI classifiers. To address these challenges, we propose CoPath, a framework consisting of CoHisNet and PathVote. CoHisNet is a lightweight multi-scale feature-fusion network for patch-level histopathological classification. By replacing the multilayer perceptron components in Swin Transformer blocks and the classification head with Kolmogorov-Arnold Network layers, CoHisNet improves nonlinear feature modeling under a compact architecture. Its multi-scale interaction and contrast-driven feature-enhancement design enables the model to capture both tissue-level structures and fine-grained cellular morphology. PathVote further incorporates pathology-informed tissue-component priors to aggregate patch-level predictions into WSI-level decisions. We validated CoPath on a private two-branch PpNTs cohort and the public BreakHis breast cancer histopathology dataset. Experimental results show that CoPath achieves competitive or superior performance compared with general image classifiers, pathology foundation models under linear probing, and pathology-specific classification models, while maintaining substantially lower computational complexity. The source code is available atthis https URL.
  </details>

- **[Learning To Focus: Anatomy-Guided Attention Regularization for Medical Image Classification](https://arxiv.org/abs/2607.10851)**  `arXiv:2607.10851`  `cs.CV`  
  _Tonmoy Hossain, Atiqur Rahman, Farhana Hossain Swarnali, Miaomiao Zhang_
  <details open><summary>Abstract</summary>
  Medical image classification models are ideally expected to identify diagnostically relevant regions while making predictions, yet standard classification losses rarely provide spatial supervision. Explicit supervision via anatomical shape information, such as segmentation masks of task-relevant anatomy, has been shown to guide the network toward regions relevant to the target prediction. However, obtaining such masks incurs substantial manual annotation effort and computational overhead. With the advent of segmentation foundation models that exhibit strong localization of anatomical structures across diverse imaging modalities, we leverage this capability to extract anatomical shape priors without the burden of training a dedicated segmentation model. In this paper, we propose a new framework, Locus, an anatomical attention regularization framework that leverages pretrained segmentation foundation models to guide a classifier's attention toward diagnostically meaningful anatomical structures across diverse imaging modalities. Instead of enforcing pixel-wise alignment with the foundation-model-derived mask, we introduce a regularization term that adaptively balances attention between anatomical (foreground) and background regions, penalizing the classifier when background attention dominates. We validate Locus on eight diverse medical imaging datasets spanning dermoscopy, X-ray, histopathology, and cardiac MRI, showing consistent gains in classification performance alongside improved anatomically grounded attention.
  </details>
