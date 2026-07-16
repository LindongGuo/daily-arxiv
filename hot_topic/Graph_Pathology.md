# 🔍 Graph_Pathology Papers · 2026-07-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[CDS: Counterfactual Directionality Score for Structured Interventions in Spatial Graphs](https://arxiv.org/abs/2607.13508)**  `arXiv:2607.13508`  `cs.LG`  
  _Humaira Anzum, Md Ishtyaq Mahmud, Jagan Mohan Reddy Dwarampudi, Tania Banerjee_
  <details open><summary>Abstract</summary>
  Quantifying directional influence between node populations is a fundamental problem in graph-based modeling, particularly in spatial biological systems where cell-cell interactions shape functional outcomes. Existing approaches based on attention, attribution, or correlation capture associations but do not provide a principled framework for evaluating directional effects under controlled perturbations. We introduce a framework for structured counterfactual interventions in graph-based models to estimate directional influence between node types. Our approach trains a Neighbor Influence Model (NIM) to predict node states from local neighborhoods and applies constrained interventions that modify neighborhood composition while preserving key spatial and structural properties. We define the Counterfactual Directionality Score (CDS), which measures the change in predicted node state induced by targeted perturbations, and provide a theoretical interpretation of CDS as a finite-difference measure of local intervention sensitivity. To obtain valid uncertainty estimates, we introduce a core-level bootstrap procedure that accounts for dependencies within spatial samples. Experiments on synthetic spatial graphs with known directional structure show that CDS recovers directional influence, remains well calibrated under null conditions, and is robust to confounding signals, while preliminary results on spatial transcriptomics data reveal biologically plausible and consistent interactions across tissue cores.
  </details>
