# 🔍 Multimodal_ST_Pathology Papers · 2026-08-23

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[CellPath-Bench: A Multidimensional Benchmark for Whole-Slide Cellular Representations in Pathology Foundation Models](https://arxiv.org/abs/2608.21060)**  `arXiv:2608.21060`  `cs.AI` `cs.CV`  
  _Bokai Zhao, Yiyang Zhang, Hanqing Chao, Yawei Ma, Long Bai, Tai Ma, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) are increasingly used as general-purpose backbones, yet existing benchmarks cannot systematically diagnose their whole-slide cellular representation capabilities, including the decodability of cell-type information and the transferability of such information across tissue sections, datasets, and anatomical organs. We introduce CellPath-Bench, a cellular-resolution benchmark that evaluates frozen PFMs themselves. Following quality control of 52 candidate Xenium datasets, we construct a panel of 25 spatially aligned H\&E--Xenium tissue sections spanning 11 organs and 7,079,283 cells, harmonized into fine- and coarse-grained taxonomies. CellPath-Bench samples frozen WSI feature maps at registered nuclear coordinates and evaluates them using standardized multiclass linear probes. Cell Representation Advantage (CRA) measures the within-section advantage of nucleus-anchored representations over patch-level mean pooling, while Cell Representation Transferability (CRT) characterizes the generalization of cell-type decodability across tissue sections, datasets, and organs. We benchmark 30 pathology-specific and general-purpose foundation models through 304,920 runs across spatial readouts, magnifications, taxonomic granularities, and evaluation protocols. The results reveal substantial model-dependent differences in cell-type decodability and its cross-domain generalization, yielding distinct multidimensional capability profiles. CellPath-Bench provides a standardized framework for auditing cellular information in frozen PFM representations.
  </details>
