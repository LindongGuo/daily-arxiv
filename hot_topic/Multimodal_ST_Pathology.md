# 🔍 Multimodal_ST_Pathology Papers · 2026-06-30

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MSNN-LINet: Cross-Modal Learning via Continuous Linear Integration](https://arxiv.org/abs/2606.31135)**  `arXiv:2606.31135`  `cs.CV` `cs.LG`  
  _Gabriel Clinger_
  <details open><summary>Abstract</summary>
  We present LINet (Linear Integration Network), a Multi-Stream Neural Network (MSNN) for RGB-D scene classification. Current multi-modal architectures treat feature fusion as a discrete, ad-hoc event: early fusion entangles representations prematurely, late fusion isolates them until the final layer, and hybrid or attention-based methods require architectural guesswork to place intermediate fusion blocks. LINet addresses this structural compromise by maintaining three dedicated parallel streams (RGB, depth, and integration) where a novel Linear Integration Convolution (LIConv2d) operator enables continuous cross-modal learning at every layer. The integration stream receives raw filtered signals from both modality streams and combines them before the nonlinear activation threshold, conceptually inspired by somatic integration preceding the neuronal firing decision. Implementing continuous integration exposes a critical initialization pathology: Kaiming initialization of the bridging weights scrambles gradients before they reach the stream backbones, producing a failure mode that resembles overfitting but is corrupted gradient flow. A 1/N constant initialization mitigates this. We employ progressive modality dropout, a curriculum adapted to continuous fusion in which blanking probability increases from zero, preventing pathway collapse, a form of negative co-learning, by forcing robust independent stream representations. Trained from scratch on SUN RGB-D 19-class scene classification, LINet reaches 45.2% mean class accuracy at ResNet18 scale, outperforming prior from-scratch results, and rises to 49.6% with in-domain RGB-D (ScanNet) pretraining.
  </details>
