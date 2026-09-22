# 🔍 ST_Generation_Imputation Papers · 2026-09-21

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Generating Chest X-Ray Counterfactuals by Specialising Foundation Image Models](https://arxiv.org/abs/2609.24879)**  `arXiv:2609.24879`  `cs.CV`  
  _Xiaodan Xing, Rajat R. Rasal, Julia A. Meister, Sara Ghorayeb, Galvin Khara, Jessica Schrouff_
  <details open><summary>Abstract</summary>
  Counterfactual image generation answers questions about how a subject would have looked under retrospective, hypothetical scenarios. Recent methods have improved perceptual quality, identity preservation and faithfulness to an underlying causal model, but their adoption in healthcare is limited by scarce annotated data, distribution shift between datasets, and mismatches between pretrained generative models and those required for counterfactual inference. We propose specialisation, a data and parameter-efficient framework for adapting pretrained, non-causal generative models into causal mechanisms under distribution shift. Based on this framework, we train a radiology counterfactual image generation model, called RadCF, using latent flow matching. We validate our approach on three chest X-ray datasets spanning different dataset shifts, data volumes, and counterfactual questions, associated with challenging, highly-localised interventions. Our results show that RadCF and specialisation improve counterfactual soundness over existing methods while being data and parameter efficient, and that the resulting counterfactuals can detect and mitigate shortcut learning in a downstream medical classifier. Code is available atthis https URL.
  </details>

- **[Metadata Supervised Imaging Representations for Modelling and Controlling Acquisition Variability](https://arxiv.org/abs/2607.11295)**  `arXiv:2607.11295`  `cs.CV`  
  _Mehmet Yigit Avci, Pedro Borges, Virginia Fernandez, Natalia Glazman, Paul Wright, Mehmet Yigitsoy, et al._
  <details open><summary>Abstract</summary>
  Biomedical imaging data exhibit substantial acquisition variability, where identical biological structures can appear markedly different due to differences in imaging devices, acquisition protocols, sites, and reconstruction settings. Consequently, learned representations often entangle underlying biological information with acquisition-dependent appearance, limiting interpretability, generalisation, and clinical deployment. We show that these sources of variation can be disentangled by jointly modelling medical images and acquisition metadata. Using large-scale clinical brain MRI data as a case study, we learn representations that disentangle anatomical structure from contrast-dependent appearance. The resulting framework enables the organisation of heterogeneous imaging protocols, sequence understanding, the detection of image-metadata inconsistencies and imaging artifacts, while preserving biologically relevant anatomical features across diverse acquisitions. Building on these disentangled representations, it further supports generative and translational capabilities, performing both metadata-conditioned synthesis of realistic 3D brain MRIs and anatomy-preserving harmonisation for cross-modality and cross-site adaptation. Our findings demonstrate that acquisition variability is a structured component of the imaging process that can be modeled, audited, synthesised, and controlled, establishing a foundation for acquisition-aware representation learning in large-scale biomedical imaging.
  </details>
