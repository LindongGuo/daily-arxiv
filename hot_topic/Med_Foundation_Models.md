# 🔍 Med_Foundation_Models Papers · 2026-03-10

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Class Visualizations and Activation Atlases for Enhancing Interpretability in Deep Learning-Based Computational Pathology](https://arxiv.org/abs/2603.07170)**  `arXiv:2603.07170`  `cs.CV`  
  _Marco Gustav, Fabian Wolf, Christina Glasner, Nic G. Reitsam, Stefan Schulz, Kira Aschenbroich, et al._
  <details open><summary>Abstract</summary>
  The rapid adoption of transformer-based models in computational pathology has enabled prediction of molecular and clinical biomarkers from H&E whole-slide images, yet interpretability has not kept pace with model complexity. While attribution- and generative-based methods are common, feature visualization approaches such as class visualizations (CVs) and activation atlases (AAs) have not been systematically evaluated for these models. We developed a visualization framework and assessed CVs and AAs for a transformer-based foundation model across tissue and multi-organ cancer classification tasks with increasing label granularity. Four pathologists annotated real and generated images to quantify inter-observer agreement, complemented by attribution and similarity metrics. CVs preserved recognizability for morphologically distinct tissues but showed reduced separability for overlapping cancer subclasses. In tissue classification, agreement decreased from Fleiss k = 0.75 (scans) to k = 0.31 (CVs), with similar trends in cancer subclass tasks. AAs revealed layer-dependent organization: coarse tissue-level concepts formed coherent regions, whereas finer subclasses exhibited dispersion and overlap. Agreement was moderate for tissue classification (k = 0.58), high for coarse cancer groupings (k = 0.82), and low at subclass level (k = 0.11). Atlas separability closely tracked expert agreement on real images, indicating that representational ambiguity reflects intrinsic pathological complexity. Attribution-based metrics approximated expert variability in low-complexity settings, whereas perceptual and distributional metrics showed limited alignment. Overall, concept-level feature visualization reveals structured morphological manifolds in transformer-based pathology models and provides a framework for expert-centered interrogation of learned representations across label granularities.
  </details>
