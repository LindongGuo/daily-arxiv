# 🔍 Graph_Pathology Papers · 2026-06-01

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[PathAR: Structure-First Autoregressive Synthesis of Multimodal Pathology Images](https://arxiv.org/abs/2606.01543)**  `arXiv:2606.01543`  `cs.CV`  
  _Yuan Zhang, Jiahao Xia, Junzhang Huang, Meng Wang, Feng Chen, Guanyu Yang, et al._
  <details open><summary>Abstract</summary>
  Data scarcity in multimodal pathology motivates unified generative models that synthesize modality-specific appearance while preserving anatomically coherent structure. Although modalities differ in appearance statistics, morphological structures such as cellular topology and tissue boundaries are largely preserved across acquisition protocols. However, existing methods often model these factors within a homogeneous token stream, implicitly coupling structure with appearance and weakening structural controllability under modality shifts. To address this, we propose pathology Autorgressive modeling (PathAR), a structure-first autoregressive synthesis framework that explicitly factorizes structure and appearance for modality-label-conditioned pathologythis http URLemploys a dual vector quantization (Dual-VQ) tokenizer to decompose samples into mask-grounded structure and appearance tokens, and an interleaved autoregressive (IAR) transformer with asymmetric attention visibility to enforce structure-to-appearance dependence. PathAR stabilizes morphology under heterogeneous modality-specific appearances and enables spatially aligned image--mask pair generation. Extensive experiments show that PathAR improves structural consistency and modality fidelity over baselines, maintains sample diversity, supports downstream segmentation in data-scarce regimes, and demonstrates extensibility to finer-grained intra-modality organ-label variation.
  </details>
