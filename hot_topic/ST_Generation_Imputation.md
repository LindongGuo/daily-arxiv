# 🔍 ST_Generation_Imputation Papers · 2026-09-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[EssentialGIN: a new approach for gene essentiality prediction based on graph isomorphism neural networks](https://arxiv.org/abs/2606.07700)**  `arXiv:2606.07700`  `cs.LG` `cs.AI`  
  _Sahar Mansouri-Rad, Zahra Narimani, Parvin Razzaghi, Nazanin Hosseinkhan_
  <details open><summary>Abstract</summary>
  Background: Prediction of essential genes (proteins), is a basic and challenging problem but at the same time very costly and time-consuming in wet-lab experiments. Predicting essential genes, only based on computational methods (to introduce wet-lab candidates) using centrality measures are not accurate and result in large number of false positives; therefore, more complex models such as deep learning and also integration of biological information are used in recent research to identify essential genes.Methods: In this work we focus on graph isomorphism networks, in order to embed proteins as a node in PPI network to conserve topological features of PPI network, and also integrate biological data such as gene expression data, gene orthology information and gene subcellular localization information, and introduced a deep architecture for predicting essential genes. Graph isomorphism network architecture is modified in this work for embedding node information.Results: Our experiments proved that the proposed method outperforms baseline centrality-based methods and also machine learning based methods such as Node2Vec, MLP, and also graph attention networks (GAT).Conclusion: In this paper we observed that using graph isomorphism networks that integrate biological data (as node attributes) and preserve network topology can significantly improve the essential gene prediction accuracy. In simpler organisms such as E. coli and D. melanogaster, methods such as multi-layer perceptron using Node2Vec embedding also performs very good, but in H. sapiens the introduced architecture significantly outperforms deep learning and other graph neural network solutions.Keywords: Essential gene prediction, graph neural network, graph isomorphism network, PPI network, node embedding
  </details>

- **[Fast Cross-Strength Multi-Contrast Brain MRI Translation using Latent Bridge Matching](https://arxiv.org/abs/2609.20341)**  `arXiv:2609.20341`  `cs.CV` `cs.LG`  
  _Siddharth Srivastava, Till Bretschneider_
  <details open><summary>Abstract</summary>
  Magnetic Resonance Imaging (MRI) acquired at different field strengths exhibits pronounced variation in noise, resolution, homogeneity, and contrast, which limits comparability across acquisition settings and complicates downstream analysis. We address this with a unified conditional model for controllable field-to-field synthesis, built on the framework of conditional latent bridge matching. Our single model achieves highly competitive results across the validation phase for all three tasks of the MRIxFields2026 challenge without task-specific architectures or training. We achieve fast generation with only a single inference step, producing all modality and field-strength combinations for $30$ axial slices in under $90$ seconds, as well as cross-modality-strength translation for a full volume in under $70$ seconds, on a single NVIDIA A5000 GPU. We further provide extensive ablations regarding different components of our solution. Code:this https URL
  </details>
