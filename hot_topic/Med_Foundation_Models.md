# 🔍 Med_Foundation_Models Papers · 2026-08-23

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
  Pathology foundation models encode non-biological variation introduced by tissue preparation, staining and scanning, enabling shortcut learning that undermines generalisation across institutions. The Robustness Index (RI) was proposed to assess whether local representation geometry is dominated by biological or non-biological variation. However, its construction suffers from structural limitations that make cross-model comparison unreliable, calling for a more principled metric. We introduce the Cross-confounder Robustness Margin (CRoMa), a signed, per-sample margin that measures whether samples sharing the same biology but different confounder lie closer than samples sharing the same confounder but different biology. It is defined for every sample, allowing models to be compared on the same cohort and robustness to be analysed as a distribution rather than reduced to a single pooled score. We evaluated CRoMa across 20 tile-level encoders on three benchmarks. Rankings by median CRoMa were highly consistent across benchmarks (Spearman rho ~ 0.90), yet every encoder retained confounder-dominated samples, whose prevalence and severity varied markedly. Similar patterns emerged for four slide-level encoders evaluated on a separate benchmark, extending the analysis beyond tile-level representations. Higher median CRoMa was associated with smaller shortcut-induced performance losses in downstream linear probes, supporting its use as a representation-level indicator of shortcut susceptibility.
  </details>

- **[CellPath-Bench: A Multidimensional Benchmark for Whole-Slide Cellular Representations in Pathology Foundation Models](https://arxiv.org/abs/2608.21060)**  `arXiv:2608.21060`  `cs.AI` `cs.CV`  
  _Bokai Zhao, Yiyang Zhang, Hanqing Chao, Yawei Ma, Long Bai, Tai Ma, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) are increasingly used as general-purpose backbones, yet existing benchmarks cannot systematically diagnose their whole-slide cellular representation capabilities, including the decodability of cell-type information and the transferability of such information across tissue sections, datasets, and anatomical organs. We introduce CellPath-Bench, a cellular-resolution benchmark that evaluates frozen PFMs themselves. Following quality control of 52 candidate Xenium datasets, we construct a panel of 25 spatially aligned H\&E--Xenium tissue sections spanning 11 organs and 7,079,283 cells, harmonized into fine- and coarse-grained taxonomies. CellPath-Bench samples frozen WSI feature maps at registered nuclear coordinates and evaluates them using standardized multiclass linear probes. Cell Representation Advantage (CRA) measures the within-section advantage of nucleus-anchored representations over patch-level mean pooling, while Cell Representation Transferability (CRT) characterizes the generalization of cell-type decodability across tissue sections, datasets, and organs. We benchmark 30 pathology-specific and general-purpose foundation models through 304,920 runs across spatial readouts, magnifications, taxonomic granularities, and evaluation protocols. The results reveal substantial model-dependent differences in cell-type decodability and its cross-domain generalization, yielding distinct multidimensional capability profiles. CellPath-Bench provides a standardized framework for auditing cellular information in frozen PFM representations.
  </details>
