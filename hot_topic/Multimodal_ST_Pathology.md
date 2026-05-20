# 🔍 Multimodal_ST_Pathology Papers · 2026-05-19

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MSAlign: Aligning Molecule and Mass Spectra Foundation Models for Metabolite Identification](https://arxiv.org/abs/2605.19752)**  `arXiv:2605.19752`  `cs.LG`  
  _Paul Krzakala, Gabriel Melo, Camille Lançon, Charlotte Laclau, Rémi Flamary, Etienne Thévenot, et al._
  <details open><summary>Abstract</summary>
  Accurately identifying metabolites i.e. small molecules from mass spectrometry data remains a core challenge in metabolomics, with broad applications in drug discovery, environmental analysis, and clinical research. We address the Molecule Retrieval task, which consists in recovering the chemical structure of a metabolite from its MS/MS spectrum given a set of candidate molecules. While the recent release of benchmark datasets such as MassSpecGym and Spectraverse has considerably accelerated the development of novel machine learning approaches, the complexity of data preprocessing pipelines and the lack of unified implementations make methods and results difficult to reproduce and compare. We make three contributions. First, we propose a unified framework encompassing recent approaches based on representation alignment and contrastive learning. Second, we introduce MSAlign, inspired by multimodal alignment in vision-language models, which learns a shared representation space by aligning two frozen foundation models (DreaMS for mass spectra and ChemBERTa for molecules) through lightweight MLP projections trained with a candidate-based contrastive objective. MSAlign is simple to implement, fast to train and consistently outperforms existing approaches across all benchmarks. Third, we investigate a long-standing evaluation problem: data splitting strategies in molecule retrieval implicitly trade off data leakage against domain shift. We formalize this tension by introducing a quantitative measure of distribution shift, and use it to evaluate splitting strategies in existing benchmarks. All datasets, splits, candidate sets, and a unified implementation of MSAlign and baselines are publicly released to support reproducible research.
  </details>
