# 🔍 Multimodal_ST_Pathology Papers · 2026-08-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Disentangled Shared Representations Improve Morpho-Transcriptomic Integration](https://arxiv.org/abs/2608.14355)**  `arXiv:2608.14355`  `cs.AI`  
  _Julian Ostermaier, Swann Ruyter, Reuben Dorent, Daniel Racoceanu_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables the simultaneous profiling of gene expression and tissue morphology, creating an opportunity to learn multimodal representations capturing shared morpho-transcriptomic structure. However, standard multimodal models often compress modalities into a common latent space without explicitly separating shared and modality-specific sources of variation, which may limit downstream utility. We investigate whether explicit disentanglement of shared and private latent components improves multimodal representation learning for paired Hematoxylin \& Eosin (H\&E) and ST data. We compare VAE-based and contrastive approaches, each in standard and disentangled variants, across two cancer cohorts under matched experimental conditions. Representations are evaluated using cross-modal reconstruction, downstream probing and cross-modal probe transfer. The experiments suggest two main trends. First, contrastive objectives yield higher downstream probing performance than VAE-based models. Second, disentangled variants improve the selected reconstruction and probing metrics, although the gains depend on the model family, task, direction, and disentanglement strength. Overall, our results suggest that explicitly factorizing shared and modality-specific information can improve multimodal representation learning for spatial transcriptomics and provides a useful evaluation framework for future foundation models.
  </details>

- **[Program-space Diffusion for Morphology-to-Transcriptomics Prediction](https://arxiv.org/abs/2608.14330)**  `arXiv:2608.14330`  `cs.AI`  
  _Ruyter Swann, Dorent Reuben, Racoceanu Daniel_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables genome-wide gene expression profiling while preserving tissue architecture, but its cost and limited scalability remain major bottlenecks. This has motivated models that predict spatial expression directly from routine histology. Despite promising results, most existing approaches operate at the gene level without leveraging established transcriptomic modeling practices and rely on heterogeneous gene selection strategies, which complicates fair comparison across methods.We propose to reformulate morphology-to-transcriptomics prediction as conditional generation in transcriptional program space, thereby exploiting coordinated transcriptional variation instead of predicting genes independently. Using consensus non-negative matrix factorization (cNMF), we extract a low-dimensional set of transcriptional programs capturing coordinated expression variation in the training data, and train a conditional diffusion model to generate program activations from histology. This formulation exploits coordinated transcriptional variation and substantially lowers the dimensionality of the conditional generative task.
  </details>
