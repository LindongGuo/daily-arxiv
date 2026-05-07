# 🔍 Multimodal_ST_Pathology Papers · 2026-05-06

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[HEXST: Hexagonal Shifted-Window Transformer for Spatial Transcriptomics Gene Expression Prediction](https://arxiv.org/abs/2605.04682)**  `arXiv:2605.04682`  `cs.LG` `cs.CV`  
  _Keunho Byeon, Jin Tae Kwak_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics offers spatially resolved gene expression profiling within tissue sections, but its cost and limited throughput hinder large-scale deployment. To extend this capability to routine practice, recent computational methods aim to infer spatial gene expression directly from ubiquitous hematoxylin and eosin-stained histology slides. However, most existing models assume Cartesian or geometry-agnostic locality, despite the hexagonal sampling of widely used spot-array platforms, and point-wise regression objectives often yield over-smoothed gene expression profiles, obscuring gene-specific spatial heterogeneity. To address these, we propose HEXST, a geometry-aligned Transformer for spatial gene expression prediction from histology. HEXST operates directly on hexagonal spot coordinates to enable efficient local-to-global contextual modeling via tailored shifted-window attention mechanism and hexagonal rotary positional encoding. To enhance gene-wise spatial contrast, HEXST complements point-wise regression with a contrast-sensitive differential objective and transcriptomic priors from a pretrained single-cell foundation model during training. Across seven spatial transcriptomics datasets, HEXST consistently outperforms state-of-the-art models, providing accurate and robust spatial gene expression predictions while preserving gene-wise contrast and spatial heterogeneity.
  </details>

- **[MoLF: Mixture-of-Latent-Flow for Pan-Cancer Spatial Gene Expression Prediction from Histology](https://arxiv.org/abs/2602.02282)**  `arXiv:2602.02282`  `cs.LG`  
  _Susu Hu, Stefanie Speidel_
  <details open><summary>Abstract</summary>
  Inferring spatial transcriptomics (ST) from histology enables scalable histogenomic profiling, yet current methods are largely restricted to single-tissue models. This fragmentation fails to leverage biological principles shared across cancer types and hinders application to data-scarce scenarios. While pan-cancer training offers a solution, the resulting heterogeneity challenges monolithic architectures. To bridge this gap, we introduce MoLF (Mixture-of-Latent-Flow), a generative model for pan-cancer histogenomic prediction. MoLF leverages a conditional Flow Matching objective to map noise to the gene latent manifold, parameterized by a Mixture-of-Experts (MoE) velocity field. By dynamically routing inputs to specialized sub-networks, this architecture effectively decouples the optimization of diverse tissue patterns. Our experiments demonstrate that MoLF establishes a new state-of-the-art, consistently outperforming both specialized and foundation model baselines on pan-cancer benchmarks. Furthermore, MoLF exhibits zero-shot generalization to cross-species data, suggesting it captures fundamental, conserved histo-molecular mechanisms.
  </details>
