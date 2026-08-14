# 🔍 Med_Foundation_Models Papers · 2026-08-13

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[A Distributional Robustness Margin For Pathology Foundation Models](https://arxiv.org/abs/2607.25497)**  `arXiv:2607.25497`  `cs.CV` `cs.AI`  
  _Clément Grisi, Jeroen van der Laak, Geert Litjens_
  <details open><summary>Abstract</summary>
  Pathology foundation models encode non-biological variation introduced by tissue preparation, staining and scanning, enabling shortcut learning that undermines generalisation across institutions. The Robustness Index (RI} was proposed to assess whether local representation geometry is dominated by biological or non-biological variation. However, its construction suffers from structural limitations that make cross-model comparison unreliable and call for a more principled metric. We introduce the Cross-confounder Robustness Margin (CRoMa), which measures, for each sample, whether biologically matched samples differing in the confounder lie closer in representation space than confounder-matched samples differing in biology. By design, CRoMa recasts robustness as a cohort-wide distribution of sample-level margins. We evaluated frozen representations from 20 tile-level encoders across three benchmarks and 4 slide-level encoders on a fourth. Median CRoMa rankings were broadly consistent across cohorts, yet all encoders contained confounder-dominated subsets whose prevalence and severity varied substantially across models and cohorts. Higher CRoMa margins were associated with smaller shortcut-induced performance drops after supervised adaptation, indicating that CRoMa can be a valuable tool for assessing model robustness on downstream tasks.
  </details>

- **[Pathryoshka: Compressing Pathology Foundation Models via Multi-Teacher Knowledge Distillation with Nested Embeddings](https://arxiv.org/abs/2511.23204)**  `arXiv:2511.23204`  `cs.CV`  
  _Christian Grashei, Christian Brechenmacher, Rao Muhammad Umer, Jingsong Liu, Carsten Marr, Peter J. Schüffler, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) have driven significant progress in computational pathology. However, these high-performing models can easily exceed a billion parameters and produce high-dimensional embeddings, thus limiting their applicability for research or clinical use when computing resources are tight. Here, we introduce Pathryoshka, a multi-teacher distillation framework inspired by RADIO distillation and Matryoshka Representation Learning to reduce pathology FM sizes while allowing for adaptable embedding dimensions. We evaluate our framework with a distilled model on ten public pathology benchmarks with varying downstream tasks. Compared to its much larger teachers, Pathryoshka reduces the model size by 86-92% at on-par performance. It outperforms state-of-the-art single-teacher distillation models of comparable size by a median margin of 7.0 in accuracy. By enabling efficient local deployment without sacrificing accuracy or representational richness, Pathryoshka democratizes access to state-of-the-art pathology FMs for the broader research and clinical community.
  </details>
