# 🔍 Prognosis_Survival Papers · 2026-06-02

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Graph Mamba Survival Analysis Based on Topology-Aware ordering](https://arxiv.org/abs/2606.02602)**  `arXiv:2606.02602`  `cs.LG` `cs.CV`  
  _Yuanfang Chen, Peiqiang Yan, Yuntao Shou, Qian Zhao, Xiangyong Cao_
  <details open><summary>Abstract</summary>
  In computational pathology, Whole Slide Images (WSIs) survival analysis is crucial for patient prognosis assessment, but it faces multiple technical challenges. Although the Transformer captures long-range dependencies through its self-attention mechanism, its $O(N^2)$ time complexity causes a severe computational bottleneck in large-scale WSIs graph structures. The Mamba model breaks through the Transformer's computational bottleneck with linear complexity. But, owing to Mamba's high sensitivity to the order of input data, traditional node sorting methods in Graph Mamba, such as those based on node degree or subgraph size, fail to adequately account for the topological connectivity of graph data. This inadequacy consequently restricts the performance of Mamba's sequential modeling. Moreover, its unidirectional architecture cannot leverage the bidirectional spatial structure of images. To address these challenges, this paper proposes a novel Graph Mamba survival analysis framework based on topology-aware ordering (TopoMamSurv) to adapt to the sequential sensitivity of Mamba. Our visualization experiments further confirmed that the nodes extracted through the topology-aware ordering (TAO) strategy indeed exhibit higher similarity. Furthermore, we designed a bidirectional Mamba module and integrated a Graph Convolutional Network (GCN) to achieve bidirectional spatial context modeling of images, forming a hierarchical feature learning architecture for "local aggregation - global capture." This framework effectively reconciles the contradiction between long-range dependency modeling, computational efficiency, and spatial structure utilization in WSIs analysis through its systematic design of TAO, bidirectional semantic modeling, and hierarchical feature fusion. This framework has been validated for its comprehensive performance advantage on five TCGA datasets.
  </details>
