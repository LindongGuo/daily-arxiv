# 🔍 Graph_Pathology Papers · 2026-09-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Decentralized Gossip Learning and Federated Averaging for Histopathology Image Classification](https://arxiv.org/abs/2609.16448)**  `arXiv:2609.16448`  `cs.CV` `cs.LG`  
  _Yusuf Ozturk, Enes Goltekin, Bengisu Atli, Akin Ozturk, Ulas Bagci_
  <details open><summary>Abstract</summary>
  Breast histopathology analysis increasingly relies on distributed learning because direct data pooling across institutions is often restricted by privacy, governance, and communication constraints. This study compares server-based Federated Averaging (FedAvg), fully decentralized gossip learning, and Hybrid Gossip-FedAvg for invasive ductal carcinoma (IDC) patch classification. Experiments used 277,524 color image patches with patient-disjoint training, validation, and test partitions and a workload-balanced, Dirichlet-guided allocation across six nodes. Ring, random degree-3, and fully connected gossip topologies were evaluated together with sensitivity analyses for statistical heterogeneity, mixing coefficient, learning rate, model drift, prediction disagreement, calibration, clinically motivated operating points, communication payload, and patient-level IDC burden, together with auxiliary backbone robustness analyses. In the principal alpha=0.3 experiment, Hybrid Gossip-FedAvg achieved a test area under the receiver operating characteristic curve (ROC-AUC) of 0.8811, closely followed by FedAvg at 0.8801 and fully connected gossip at 0.8751. Across three independent patient-level repetitions, FedAvg and Hybrid Gossip-FedAvg obtained the same mean ROC-AUC of 0.9082, with standard deviations of 0.0037 and 0.0043, respectively. Hybrid achieved the highest mean area under the precision-recall curve of 0.8240, whereas FedAvg produced the lowest mean Brier score of 0.1335. Denser gossip graphs improved discrimination but increased theoretical model payload, while ring gossip remained sensitive to learning rate and mixing strength. Overall, FedAvg provided the most consistently reliable server-based baseline, topology-aware gossip offered a viable decentralized alternative, and Hybrid Gossip-FedAvg provided a balanced compromise between peer-to-peer diffusion and periodic global coordination.
  </details>
