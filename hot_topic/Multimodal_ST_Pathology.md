# 🔍 Multimodal_ST_Pathology Papers · 2026-04-03

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Towards Faithful Reasoning in Comics for Small MLLMs](https://arxiv.org/abs/2601.02991)**  `arXiv:2601.02991`  `cs.CV` `cs.AI`  
  _Chengcheng Feng, Haojie Yin, Yucheng Jin, Kaizhu Huang_
  <details open><summary>Abstract</summary>
  Comic understanding presents a significant challenge for Multimodal Large Language Models (MLLMs), as the intended meaning of a comic often emerges from the joint interpretation of visual, textual, and social cues. This naturally motivates Chain-of-Thought (CoT) prompting, since explicit intermediate reasoning appears promising for integrating such heterogeneous signals. However, existing CoT methods are poorly matched to this structure: they tend to force interpretation into a single reasoning path before multiple cues have been jointly considered, often degrading performance, especially for small MLLMs. Our key idea is to explicitly preserve multi-cue interpretation during supervision construction, rather than collapsing comic understanding into a single reasoning chain. To this end, we propose a two-stage framework for faithful comic reasoning in small MLLMs. First, we introduce MoCoT, a modular supervision construction framework that preserves multi-cue interpretation and turns it into more faithful supervision. Second, we propose VERA, a structured reward mechanism that turns such supervision into faithful reasoning behavior by aligning optimization with both reasoning faithfulness and answer correctness. Extensive experiments on five benchmarks spanning comic understanding and broader humor-centric and abstract visual reasoning tasks demonstrate that our framework achieves strong results in the $\leq$ 4B regime, surpasses several 7B baselines, improves four small MLLMs by an average of $\mathbf{12.1%}$ as a plug-in, and consistently enhances reasoning faithfulness while preserving inference efficiency.
  </details>
