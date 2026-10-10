# 🔍 Multimodal_ST_Pathology Papers · 2026-10-09

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[PathLang: A Language-Centered Benchmark for Vision-Language Models in Computational Pathology](https://arxiv.org/abs/2610.11329)**  `arXiv:2610.11329`  `cs.CV`  
  _Fanqi Cheng, Kuo Gong, Shangke Liu, Beidi Zhao, Junchao Zhu, Zheyu Zhu, et al._
  <details open><summary>Abstract</summary>
  Pathology vision-language models (VLMs) have shown strong visual perception ability, but their robustness in the language domain remains poorly characterized. Existing pathology VLM benchmarks largely rely on canonical closed-set prompts or perturb only generic templates, treating language as a fixed evaluation component rather than a variable axis of model behavior. In clinical practice, however, diagnostic language varies across reports, institutions, and candidate diagnoses. We introduce PathLang, a language-centered and clinically grounded zero-shot benchmark. PathLang holds the underlying slides, ground-truth labels, and image-text evaluation direction fixed while systematically varying only the diagnostic language, so that performance differences reflect how a diagnosis is phrased rather than what is imaged. The language variation follows how pathologists actually rephrase diagnoses (terminology, specificity, and reporting style), and all prompts and candidate pools are validated by six board-certified pathologists. PathLang covers four task families: (1) zero-shot classification with image-text alignment analysis, (2) cross-modal retrieval, (3) paraphrase robustness, including semantic-equivalence paraphrases, length and reporting-style variation, and prompt ensembling, and (4) open-vocabulary diagnosis retrieval over four candidate pools with distinct forms of semantic competition. Across nine VLMs and five public datasets spanning four organs, we find that performance is highly sensitive to clinically equivalent paraphrases, varies substantially across forms of semantic competition, and that image-text alignment quality does not necessarily translate into inter-class separability. We release the prompt corpus, candidate pools, pre-computed text embeddings, and evaluation code atthis https URL.
  </details>
