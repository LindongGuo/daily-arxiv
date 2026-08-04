# 🔍 Multimodal_ST_Pathology Papers · 2026-08-03

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Structured Proxy Features for Multimodal NSCLC Survival Prediction from Pretreatment CT](https://arxiv.org/abs/2608.00446)**  `arXiv:2608.00446`  `cs.CV` `cs.AI`  
  _Huu Phong Nguyen, Delower Hossain, Ehsan Saghapour, Zhandos Sembay, Jake Y. Chen_
  <details open><summary>Abstract</summary>
  Lung cancer results in roughly 1.8 million fatalities annually worldwide, with non-small cell lung cancer (NSCLC) comprising the majority of cases. Despite advancements in treatment, survival stratification remains challenging due to intratumoral heterogeneity inadequately captured by conventional descriptors. Standard radiomic and deep learning techniques regard imaging features as independent quantities, overlooking structured interactions between tumor characteristics. We evaluate whether structured proxy features can enhance multimodal NSCLC survival prediction by augmenting pretreatment computed tomography (CT) representations, radiomics, and clinical variables with six simulation-derived features designed to capture interactions between heterogeneity and morphology. A radiomic-parameterized cellular automaton generates growth-rate and necrosis-ratio proxy features from baseline CT by using entropy and sphericity to compute low-dimensional proxy parameters. The imaging backbone is a Transformer-based Masked Autoencoder (TMAE), which was chosen after a systematic evaluation with alternative encoders within the same pipeline and provides attention-based visualizations that highlight tumor regions receiving higher model attention. On the public Lung1 cohort (n = 390), the primary four-modality fusion attained a C-index of 0.641 (iAUC 0.731, log-rank p < 0.001). The primary result compares favorably with prior multimodal results on Lung1 (C-index 0.631; iAUC 0.592 [15]) under a comparable evaluation protocol, while a separate exploratory coefficient-optimization analysis achieved a best observed C-index of 0.662 (iAUC 0.748). These results indicate that, in addition to conventional radiomic, deep, and clinical representations within the Lung1 benchmark, simulation-derived proxy features may provide complementary predictive information within this fixed Lung1 benchmark.
  </details>

- **[Unifying biomedical knowledge in a modern multimodal graph](https://arxiv.org/abs/2604.27269)**  `arXiv:2604.27269`  `cs.AI`  
  _Lucas Vittor, Ayush Noori, Iñaki Arango, Joaquín Polonuer, Sam Rodriques, Andrew White, et al._
  <details open><summary>Abstract</summary>
  Biomedical knowledge graphs (KGs) are widely used in the life sciences, yet many are derived from unstructured documents and therefore lack schema-level constraints, whereas graphs assembled from structured resources are difficult to harmonize into a unified representation. We present OptimusKG, a multimodal biomedical labeled property graph (LPG) built from structured and semi-structured resources to preserve factual, type-specific metadata across molecular, anatomical, clinical, and environmental domains. OptimusKG contains 190,939 nodes across 10 entity types, 21,818,752 edges across 27 edge types, and 67,070,490 property instances encoding 109,665,797 values across 145 distinct property keys, derived from 18 ontologies and controlled vocabularies. The graph enforces a top-level schema for nodes and edges and retains granular, type-specific properties, cross-references, and provenance. We assessed the validity of OptimusKG by evaluating whether graph relationships are supported by evidence from the scientific literature using a multimodal agent, PaperQA3. PaperQA3 identified supporting evidence for 70.0% of sampled edges, whereas 83.4% of sampled false edges received no supporting evidence. Edges without literature support were concentrated in associations derived from experimental and functional genomics resources, suggesting that OptimusKG captures biomedical knowledge that may precede synthesis in the scientific literature. OptimusKG is distributed as Apache Parquet files, providing a standardized resource for graph-based machine learning, knowledge-grounded retrieval with large language models, and biomedical discovery use cases such as hypothesis generation.
  </details>
