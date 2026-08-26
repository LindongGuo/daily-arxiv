# 🔍 Multimodal_ST_Pathology Papers · 2026-08-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[EviPathBench: Benchmarking Evidence Acquisition and Reasoning in Vision-Language Models for Whole-Slide Pathology](https://arxiv.org/abs/2607.19261)**  `arXiv:2607.19261`  `cs.CV` `cs.AI`  
  _Dankai Liao, Tianyi Zhang, Yufeng Wu, Xinyue Zhang, Qiaochu Xue, Zeyu Liu, et al._
  <details open><summary>Abstract</summary>
  Whole-slide image (WSI) diagnosis requires identifying diagnostically relevant regions, examining them across magnifications, and integrating multi-scale evidence. However, most pathology benchmarks evaluate models on pre-cropped patches or pre-extracted slide features, leaving their ability to acquire evidence from gigapixel WSIs largely untested. We introduce EviPathBench, a benchmark for evaluating evidence acquisition and reasoning in vision-language models (VLMs) for whole-slide pathology. It evaluates four capabilities: image-to-text matching for evidence interpretation, text-to-image retrieval for evidence verification, diagnostic-region localization for evidence acquisition, and multi-scale reasoning for evidence integration. The benchmark is organized as a diagnostic tree linking nested regions across magnifications with scale-specific findings and path-level diagnoses. It contains 1,822 TCGA WSIs and 17,135 diagnostic paths annotated by ten board-certified pathologists. A private cohort of 190 breast cancer WSIs with detailed annotations further evaluates autonomous whole-slide exploration. We evaluate 19 VLMs spanning general-purpose, medical, and pathology-specialized families, plus one text-only reference model. Leading open-weight models achieve over 93% accuracy in multi-scale reasoning and over 50% in both cross-modal matching tasks. In contrast, diagnostic-region localization remains challenging: the best text-guided mean intersection-over-union is below 0.09, underperforming a center-based heuristic. During autonomous exploration, the unconditional hit rate drops from 0.522 at low magnification to 0.185 at intermediate magnification and 0.020 at high magnification. These results reveal a pronounced gap between reasoning over curated evidence and acquiring it from WSIs. EviPathBench provides a unified framework for measuring and improving both capabilities.
  </details>
