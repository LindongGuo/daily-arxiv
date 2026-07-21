# 🔍 Prognosis_Survival Papers · 2026-07-20

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[AdaSurvMamba: Dynamic Fusion and Semantic Scanning for Multimodal Survival Analysis](https://arxiv.org/abs/2607.16260)**  `arXiv:2607.16260`  `cs.LG` `cs.AI` `cs.CV`  
  _Jialong Zhong, Tingwei Liu, Baokun Yue, Jingjing Li, Yongri Piao, Miao Zhang, et al._
  <details open><summary>Abstract</summary>
  Multimodal survival analysis utilizing whole slide images (WSIs) and genomic profiles is fundamental for cancer prognosis. Recently, state-space models like Mamba have emerged as powerful tools for sequence modeling. However, translating this success to complex multimodal tasks is hindered by two critical limitations. First, conventional fusion strategies assume a static multimodal interaction strength, ignoring the fluctuating diagnostic importance of each modality across different patients and local regions. Second, the standard Mamba architecture processes tokens along predefined physical paths. This rigid scanning disrupts the semantic continuity of spatially scattered medical features and exacerbates long-range decay. To address these challenges, we introduce AdaSurvMamba as a novel adaptive framework for multimodal survival analysis. The framework features a Dual-Scale Importance-Aware Reconstruction (DSIR) module to dynamically modulate cross-modal interaction strength. It evaluates diagnostic importance at both the sequence and token levels to reconstruct the input representations. Furthermore, we propose a Semantic Aggregation Scanning (SAS) module to overcome contextual fragmentation. The SAS module dynamically reorganizes discrete tokens into semantically continuous sequences via a shared prototype pool. It explicitly modulates the state transition step size using global modality context and semantic priors to adaptively control the information absorption rate. Experiments across five TCGA cohorts demonstrate consistent gains over existing methods. Code is available atthis https URL.
  </details>
