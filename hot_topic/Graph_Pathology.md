# 🔍 Graph_Pathology Papers · 2026-05-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Beyond Instance-Level Self-Supervision in 3D Multi-Modal Medical Imaging](https://arxiv.org/abs/2605.14654)**  `arXiv:2605.14654`  `cs.CV`  
  _Tan Pan, Shuhao Mei, Yixuan Sun, Kaiyu Guo, Chen Jiang, Zhaorui Tan, et al._
  <details open><summary>Abstract</summary>
  Self-supervised pre-training methods in medical imaging typically treat each individual as an isolated instance, learning representations through augmentation-based objectives or masked reconstruction. They often do not adequately capitalize on a key characteristic of physiological features: anatomical structures maintain consistent spatial relationships across individuals (instances), such as the thalamus being medial to the basal ganglia, regardless of variations in brain size, shape, or pathology. We propose leveraging this cross-instance topological consistency as a supervisory signal. The challenge arises from the inherent variability in medical imaging, which can differ significantly across instances and modalities. To tackle this, we focus on two alignment regimes. (i) Intra-instance: with pixel-level correspondences available, a cross-modal triplet objective explicitly preserves local neighborhood topology. (ii) Inter-instance: without such supervision, we derive pseudo-correspondences to control partial neighborhood alignment and prevent topology collapse across modalities. We validate our approach across 7 downstream multi-modal tasks, achieving average improvements of 1.1% and 5.94% in segmentation and classification tasks, respectively, and demonstrating significantly better robustness when modalities are missing at test time.
  </details>
