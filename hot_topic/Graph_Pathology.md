# 🔍 Graph_Pathology Papers · 2026-09-27

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Graph Neural Network,WSI` `GNN,Spatial Transcriptomics` `Cell-Cell Interaction` `Topology,Pathology`  
**Filter**: `None`

---

## 📚 Paper List

- **[Refining Cytology Predictions with Conditional Random Fields](https://arxiv.org/abs/2609.31028)**  `arXiv:2609.31028`  `cs.CV`  
  _Manon Dausort, Tiffanie Godelaine, Karim El Khoury, Maxime Zanella, Christophe De Vleeschouwer, Benoît Macq_
  <details open><summary>Abstract</summary>
  Vision-language models (VLMs) achieve strong zero-shot (ZS) classification on histology images but do not perform as well on cytology, whose stains and cell morphology differ markedly compared to histology. Conditional random fields (CRFs) can refine noisy VLM predictions by propagating information across patches, but existing CRF frameworks were designed for histopathology and do not transfer to cytology datasets, released as independent patch pools spanning multiple staining protocols. We introduce CytoCRF, which adapts the pairwise terms to cytology by targeting chromatin and cytology-specific staining, and further enrich the neighborhood of each potential term by combining multiple backbones. Across ten cytology datasets, CytoCRF outperforms existing CRF frameworks at every annotation budget, reaching +13.6 percentage points over the best baseline and +33.7 over ZS with only 50 annotations. Combining information from multiple backbones brings further gains, showing that the neighborhood topology matters more than the pairwise potential computed over it.
  </details>
