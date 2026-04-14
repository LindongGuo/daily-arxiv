# 🔍 ST_Generation_Imputation Papers · 2026-04-13

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Towards Autonomous Mechanistic Reasoning in Virtual Cells](https://arxiv.org/abs/2604.11661)**  `arXiv:2604.11661`  `cs.LG` `cs.AI`  
  _Yunhui Jang, Lu Zhu, Jake Fawkes, Alisandra Kaye Denton, Dominique Beaini, Emmanuel Noutahi_
  <details open><summary>Abstract</summary>
  Large language models (LLMs) have recently gained significant attention as a promising approach to accelerate scientific discovery. However, their application in open-ended scientific domains such as biology remains limited, primarily due to the lack of factually grounded and actionable explanations. To address this, we introduce a structured explanation formalism for virtual cells that represents biological reasoning as mechanistic action graphs, enabling systematic verification and falsification. Building upon this, we propose VCR-Agent, a multi-agent framework that integrates biologically grounded knowledge retrieval with a verifier-based filtering approach to generate and validate mechanistic reasoning autonomously. Using this framework, we release VC-TRACES dataset, which consists of verified mechanistic explanations derived from the Tahoe-100M atlas. Empirically, we demonstrate that training with these explanations improves factual precision and provides a more effective supervision signal for downstream gene expression prediction. These results underscore the importance of reliable mechanistic reasoning for virtual cells, achieved through the synergy of multi-agent and rigorous verification.
  </details>

- **[DiSPA: Differential Substructure-Pathway Attention for Drug Response Prediction](https://arxiv.org/abs/2601.14346)**  `arXiv:2601.14346`  `cs.LG` `cs.AI`  
  _Yewon Han, Sunghyun Kim, Eunyi Jeong, Sungkyung Lee, Seokwoo Yun, Sangsoo Lim_
  <details open><summary>Abstract</summary>
  Accurate prediction of drug response in precision medicine requires models that capture how specific chemical substructures interact with cellular pathway states. However, most existing deep learning approaches treat chemical and transcriptomic modalities independently or combine them only at late stages, limiting their ability to model fine-grained, context-dependent mechanisms of drug action. In addition, vanilla attention mechanisms are often sensitive to noise and sparsity in high-dimensional biological networks, hindering both generalization and interpretability. We present DiSPA (Differential Substructure-Pathway Attention), a framework that models bidirectional interactions between chemical substructures and pathway-level gene expression. DiSPA introduces differential cross-attention to suppress spurious associations while enhancing context-relevant interactions. On the GDSC benchmark, DiSPA achieves state-of-the-art performance, with strong improvements in the disjoint setting. These gains are consistent across random and drug-blind splits, suggesting improved robustness. Analyses of attention patterns indicate more selective and concentrated interactions compared to standard cross-attention. Exploratory evaluation shows that differential attention better prioritizes predefined target-related pathways, although this does not constitute mechanistic validation. DiSPA also shows promising generalization on external datasets (CTRP) and cross-dataset settings, although further validation is needed. It further enables zero-shot application to spatial transcriptomics, providing exploratory insights into region-specific drug sensitivity patterns without ground-truth validation.
  </details>
