# 🔍 Graph_Pathology Papers · 2026-05-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Beyond the Aggregation Dilemma: Prior-Retaining Decoupled Learning for Multimodal Graphs](https://arxiv.org/abs/2605.24684)**  `arXiv:2605.24684`  `cs.LG` `cs.AI`  
  _Hao Yan, Xuanru Wang, Jun Yin, Shirui Pan, Senzhang Wang, Chengqi Zhang_
  <details open><summary>Abstract</summary>
  Multimodal Attributed Graph Learning (MAGL) integrates intrinsic node attributes with structural topology via graph aggregation. However, as pretrained encoders evolve into Large Foundation Models (LFMs), the landscape of MAGL fundamentally shifts: under high-confidence LFM priors, mandatory aggregation introduces topological noise that overwhelms discriminative signals, triggering a counter-intuitive performance inversion where sophisticated MAGL architectures underperform simple topology-agnostic MLPs. Through systematic empirical and theoretical analysis, we identify that this inversion stems from a fundamental aggregation dilemma characterized by two concurrent pathologies: (1) Representational Pathology (SNR Degradation) - mandatory aggregation dilutes robust intrinsic features with topological noise, causing the noise penalty to outweigh its collaborative benefit; and (2) Optimization Pathology (Gradient Starvation) - topological aggregation attenuates gradient flow, while a shared task loss causes dominant modalities to prematurely suppress weaker ones. To resolve this dilemma, we propose SUPRA (Shared-Unique Prior-Retaining Architecture), a decoupled dual-pathway paradigm. SUPRA processes modality-specific features through topology-agnostic MLPs while capturing structural synergy via a lightweight shared GNN, with auxiliary deep supervision counteracting gradient starvation. Extensive evaluations demonstrate that SUPRA achieves state-of-the-art performance while requiring 3.5x lower peak GPU memory and up to 4.4x faster training time than Multimodal Graph Transformers.
  </details>
