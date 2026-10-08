# 🔍 Graph_Pathology Papers · 2026-10-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[TIRA: Tumor Immune Representation Adaptation for Zero-Shot Cross-Cancer MSI and TMB Prediction](https://arxiv.org/abs/2610.09441)**  `arXiv:2610.09441`  `cs.CV`  
  _Dasari Naga Raju_
  <details open><summary>Abstract</summary>
  Microsatellite instability-high (MSI-H) and high tumor mutational burden (TMB-H) are clinically relevant biomarkers, yet their histopathological prediction remains challenging when models are transferred across morphologically distinct cancer types. Immune-associated spatial patterns can persist across cancers despite these morphological differences, but foundation-model-based predictors trained on a single cancer do not explicitly use this information, limiting cross-cancer generalization. To address this limitation, we propose TIRA (Tumor Immune Representation Adaptation), a target-free framework that refines frozen foundation-model representations using spatial immune topology, without requiring target-domain data during model development or test-time adaptation. TIRA uses a topology-supervised biology representation to condition tile-level attention while pooling only morphological features for joint MSI and TMB prediction. We train TIRA on TCGA-COAD+READ and evaluate it zero-shot on CPTAC-COAD, TCGA-STAD, TCGA-UCEC, and CPTAC-UCEC, covering cross-site, cross-cancer, and combined cross-cancer-site distribution shifts under UNI2, CONCH, and Virchow2. With UNI2, TIRA improved zero-shot AUROC on TCGA-STAD from 0.633 to 0.766 for MSI and from 0.651 to 0.772 for TMB. Source-derived spatial immune topology improved the cross-cancer robustness of frozen pathology foundation-model representations.
  </details>
