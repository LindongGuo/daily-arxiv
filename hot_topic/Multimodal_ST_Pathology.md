# 🔍 Multimodal_ST_Pathology Papers · 2026-09-02

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Synergistic Information Disentanglement for Omni-modal Slide Representation Learning in Computational Pathology](https://arxiv.org/abs/2609.02118)**  `arXiv:2609.02118`  `cs.CV`  
  _Mingxin Liu, Chengfei Cai, Anwen Lu, Pengbo Xu, Jun Li, Jinze Li, et al._
  <details open><summary>Abstract</summary>
  In computational pathology (CPath), developing omni-modal self-supervised learning (SSL) models that integrate histology, genomics, and clinical reports enables transferable representation learning for whole slide images (WSIs). Existing approaches implicitly force heterogeneous modalities into a uniform latent space by contrastive alignment, causing modality collapse where unique, synergistic diagnostic signals (termed as $\mathrm{\Phi}$) are discarded in favor of trivial redundancy. We hypothesize that the strongest task-agnostic SSL training signal stems from distilling the synergistic interactions over merely aligning shared redundancy. To this end, we introduce \textsc{$\mathrm{\Phi}$-Omni}, a synergistic information disentanglement framework grounded in Partial Information Decomposition (PID) theory for slide representation learning. Unlike standard contrastive approaches, \textsc{$\mathrm{\Phi}$-Omni} employs a Synergistic Information Bottleneck (SIB) regulated by the proposed $\mathrm{\Phi}\text{ID}$ objective, which explicitly suppresses marginal redundancy while maximizing irreducible synergy, thereby distilling high-order cross-modal interactions. Following pretraining on breast ($n$=1031) and lung ($n$=919) cohorts, \textsc{$\mathrm{\Phi}$-Omni} demonstrates superior few-shot performance across five independent external datasets spanning eight tasks compared to supervised and SSL baselines. Source code is available here.
  </details>

- **[Unifying biomedical knowledge in a modern multimodal graph](https://arxiv.org/abs/2604.27269)**  `arXiv:2604.27269`  `cs.AI`  
  _Lucas Vittor, Ayush Noori, Iñaki Arango, Joaquín Polonuer, Sam Rodriques, Andrew White, et al._
  <details open><summary>Abstract</summary>
  Biomedical knowledge graphs (KGs) are widely used in the life sciences, yet many are derived from unstructured documents and therefore lack schema-level constraints, whereas graphs assembled from structured resources are difficult to harmonize into a unified representation. We present OptimusKG, a multimodal biomedical labeled property graph (LPG) built from structured and semi-structured resources to preserve factual, type-specific metadata across molecular, anatomical, clinical, and environmental domains. OptimusKG contains 190,939 nodes across 10 entity types, 21,818,752 edges across 27 edge types, and 67,070,490 property instances encoding 109,665,797 values across 145 distinct property keys, derived from 18 ontologies and controlled vocabularies. The graph enforces a top-level schema for nodes and edges and retains granular, type-specific properties, cross-references, and provenance. We assessed the validity of OptimusKG by evaluating whether graph relationships are supported by evidence from the scientific literature using a multimodal agent, PaperQA3. PaperQA3 identified supporting evidence for 70.0% of sampled edges, whereas 83.4% of sampled false edges received no supporting evidence. Edges without literature support were concentrated in associations derived from experimental and functional genomics resources, suggesting that OptimusKG captures biomedical knowledge that may precede synthesis in the scientific literature. OptimusKG is distributed as Apache Parquet files, providing a standardized resource for graph-based machine learning, knowledge-grounded retrieval with large language models, and biomedical discovery use cases such as hypothesis generation.
  </details>
