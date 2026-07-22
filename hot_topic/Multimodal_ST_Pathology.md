# 🔍 Multimodal_ST_Pathology Papers · 2026-07-21

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
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

- **[Advancing Multimodal Fusion on Heterogeneous Medical Data with Hybrid Geometry Attention](https://arxiv.org/abs/2607.19086)**  `arXiv:2607.19086`  `cs.CV`  
  _Joy Dhar, Manish Kumar Pandey, Nayyar Zaidi, Chen Chen, Maryam Haghighat, Ferdous Sohel, et al._
  <details open><summary>Abstract</summary>
  Multimodal fusion learning (MFL) has shown great potential in the medical domain, where we are faced with disparate data modalities such as imaging, clinical records, and omics. However, existing MFL strategies face several major challenges. First, they struggle to capture complex cross-modal interactions effectively, which in turn limits performance improvements. Second, they incur high computational costs, restricting their applicability in resource-constrained healthcare AI applications. Finally, they are often designed and evaluated for narrow, fixed modality configurations (e.g., imaging-only, or specific pairs such as image and omics), which limits evidence of their adaptability and generalizability to broader collections of heterogeneous medical modalities. To address these challenges, we propose a novel MFL framework - Cascaded Unified Representation Learning for Efficient Fusion Network (CURE) - a lightweight and scalable framework that progressively integrates various modalities through a novel efficient Hybrid Geometry Aware Fusion layer (HyFuse), where each HyFuse layer is sequentially learned for each modality, making the framework adaptable and generalizable. Within HyFuse, an efficient residual convolution module captures rich multi-scale features to ensure cost-effective learning, while a hybrid-space aware attention mixer learns coarse-to-fine structural cues to better preserve cross-modal relationships. Complementary learnable late-fusion and shared information refinement modules are then employed to learn robust modality-order-invariant shared representations, which in turn yields consistent performance improvements. Extensive evaluations on 16 public datasets show that CURE outperforms leading multimodal fusion methods, boosting performance by up to 3.97% and lowering computational costs by up to 87.8%, ensuring more effective and reliable predictions.
  </details>
