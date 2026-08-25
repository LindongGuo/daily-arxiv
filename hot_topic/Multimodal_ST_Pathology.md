# 🔍 Multimodal_ST_Pathology Papers · 2026-08-24

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[PathAgentBench: Benchmarking Evidence-Seeking Vision-Language Models on Whole-Slide Pathology Image](https://arxiv.org/abs/2607.19261)**  `arXiv:2607.19261`  `cs.CV` `cs.AI`  
  _Dankai Liao, Tianyi Zhang, Yufeng Wu, Xinyue Zhang, Qiaochu Xue, Zeyu Liu, et al._
  <details open><summary>Abstract</summary>
  Whole-slide image (WSI) diagnosis requires identifying diagnostically relevant regions, examining them across magnifications, and integrating multi-scale evidence. However, most existing pathology benchmarks evaluate models on pre-cropped patches or pre-extracted slide features, leaving their ability to acquire evidence directly from gigapixel WSIs largely untested. We introduce PathAgentBench, a benchmark for evaluating evidence-seeking vision-language models (VLMs) across four complementary capabilities: image-to-text matching for evidence interpretation, text-to-image retrieval for evidence verification, diagnostic-region localization for evidence acquisition, and multi-scale reasoning for evidence integration. The benchmark is organized as a diagnostic tree that links nested regions across magnifications with scale-specific findings and path-level diagnoses. It contains 1,822 TCGA WSIs and 17,135 diagnostic paths annotated by ten board-certified pathologists. An additional private cohort of 190 breast cancer WSIs with detailed annotations is used to evaluate autonomous whole-slide exploration. We evaluate 20 general-purpose, medical, and pathology-specialized models. Leading open-weight models achieve over 93% accuracy in multi-scale reasoning and over 50% accuracy in both cross-modal matching tasks. In contrast, diagnostic-region localization remains challenging: the best text-guided mean intersection-over-union is below 0.09, underperforming a simple center-based heuristic. During autonomous exploration, the unconditional hit rate decreases from 0.522 at low magnification to 0.185 at intermediate magnification and 0.020 at high magnification. These results reveal a pronounced gap between reasoning over curated evidence and acquiring that evidence directly from WSIs. PathAgentBench provides a unified framework for measuring and improving evidence-seeking pathology models.
  </details>
