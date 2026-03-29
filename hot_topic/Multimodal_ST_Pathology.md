# 🔍 Multimodal_ST_Pathology Papers · 2026-03-28

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[FEAST: Fully Connected Expressive Attention for Spatial Transcriptomics](https://arxiv.org/abs/2603.25247)**  `arXiv:2603.25247`  `cs.CV` `cs.AI`  
  _Taejin Jeong, Joohyeok Kim, Jinyeong Kim, Chanyoung Kim, Seong Jae Hwang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) provides spatially-resolved gene expression, offering crucial insights into tissue architecture and complex diseases. However, its prohibitive cost limits widespread adoption, leading to significant attention on inferring spatial gene expression from readily available whole slide images. While graph neural networks have been proposed to model interactions between tissue regions, their reliance on pre-defined sparse graphs prevents them from considering potentially interacting spot pairs, resulting in a structural limitation in capturing complex biological relationships. To address this, we propose FEAST (Fully connected Expressive Attention for Spatial Transcriptomics), an attention-based framework that models the tissue as a fully connected graph, enabling the consideration of all pairwise interactions. To better reflect biological interactions, we introduce negative-aware attention, which models both excitatory and inhibitory interactions, capturing essential negative relationships that standard attention often overlooks. Furthermore, to mitigate the information loss from truncated or ignored context in standard spot image extraction, we introduce an off-grid sampling strategy that gathers additional images from intermediate regions, allowing the model to capture a richer morphological context. Experiments on public ST datasets show that FEAST surpasses state-of-the-art methods in gene expression prediction while providing biologically plausible attention maps that clarify positive and negative interactions. Our code is available atthis https URLFEAST.
  </details>
