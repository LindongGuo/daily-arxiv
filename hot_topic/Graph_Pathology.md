# 🔍 Graph_Pathology Papers · 2026-09-04

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Semantic-Aware Subgraph State Space Model for WSI Classification in Histopathology](https://arxiv.org/abs/2609.03689)**  `arXiv:2609.03689`  `cs.CV`  
  _Feixing Chen, Hao Lu, Lin Luo, Yan Xu_
  <details open><summary>Abstract</summary>
  Histopathological subtyping relies on the recognition of characteristic histological patterns. These patterns may be expressed by individual tissue structures or by the spatial distribution and co-occurrence of multiple structures, and they often span irregularly shaped tissue regions, termed semantic units in this work. However, conventional patch-based representations may fragment such units and fail to explicitly preserve their internal spatial organization, while efficiently modeling relationships among numerous spatially separated units remains challenging. To address these limitations, we propose the Semantic-Aware Subgraph State Space Model (SASG-SSM), a flexible and efficient framework for whole slide image (WSI) classification. Semantic-Aware Subgraphs (SASGs) first approximate irregularly shaped semantic units by adaptively grouping spatially connected patches guided by class-agnostic visual-semantic priors. By representing patches as graph nodes with adjacency edges, SASGs preserve their internal spatial organization rather than treating them as an unordered set. A Subgraph State Space Module (SG-SSM) subsequently combines a graph neural network encoder for intra-subgraph topology encoding with a Mamba-based state space encoder for efficient contextualization across large numbers of subgraphs. This module integrates local structural information within semantic units with global contextual information arising from their distribution and co-occurrence across the WSI, while efficiently modeling a large number of spatially distributed regions. Extensive experiments across four WSI subtyping datasets demonstrate consistent advantages over representative state-of-the-art methods. Further evaluations under small-cohort and few-shot settings demonstrate robustness and data efficiency under limited training data. Code will be released atthis https URL.
  </details>
