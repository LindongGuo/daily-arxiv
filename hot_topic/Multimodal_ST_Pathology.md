# 🔍 Multimodal_ST_Pathology Papers · 2026-03-08

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[SpaCRD: Multimodal Deep Fusion of Histology and Spatial Transcriptomics for Cancer Region Detection](https://arxiv.org/abs/2603.06186)**  `arXiv:2603.06186`  `cs.CV`  
  _Shuailin Xue, Jun Wan, Lihua Zhang, Wenwen Min_
  <details open><summary>Abstract</summary>
  Accurate detection of cancer tissue regions (CTR) enables deeper analysis of the tumor microenvironment and offers crucial insights into treatment response. Traditional CTR detection methods, which typically rely on the rich cellular morphology in histology images, are susceptible to a high rate of false positives due to morphological similarities across different tissue regions. The groundbreaking advances in spatial transcriptomics (ST) provide detailed cellular phenotypes and spatial localization information, offering new opportunities for more accurate cancer region detection. However, current methods are unable to effectively integrate histology images with ST data, especially in the context of cross-sample and cross-platform/batch settings for accomplishing the CTR detection. To address this challenge, we propose SpaCRD, a transfer learning-based method that deeply integrates histology images and ST data to enable reliable CTR detection across diverse samples, platforms, and batches. Once trained on source data, SpaCRD can be readily generalized to accurately detect cancerous regions across samples from different platforms and batches. The core of SpaCRD is a category-regularized variational reconstruction-guided bidirectional cross-attention fusion network, which enables the model to adaptively capture latent co-expression patterns between histological features and gene expression from multiple perspectives. Extensive benchmark analysis on 23 matched histology-ST datasets spanning various disease types, platforms, and batches demonstrates that SpaCRD consistently outperforms existing eight state-of-the-art methods in CTR detection.
  </details>

- **[TumorChain: Interleaved Multimodal Chain-of-Thought Reasoning for Traceable Clinical Tumor Analysis](https://arxiv.org/abs/2603.05867)**  `arXiv:2603.05867`  `cs.CV`  
  _Sijing Li, Zhongwei Qiu, Jiang Liu, Wenqiao Zhang, Tianwei Lin, Yihan Xie, et al._
  <details open><summary>Abstract</summary>
  Accurate tumor analysis is central to clinical radiology and precision oncology, where early detection, reliable lesion characterization, and pathology-level risk assessment guide diagnosis and treatment planning. Chain-of-Thought (CoT) reasoning is particularly important in this setting because it enables step-by-step interpretation from imaging findings to clinical impressions and pathology conclusions, improving traceability and reducing diagnostic errors. Here, we target the clinical tumor analysis task and build a large-scale benchmark that operationalizes a multimodal reasoning pipeline, spanning findings, impressions, and pathology predictions. We curate TumorCoT, a large-scale dataset of 1.5M CoT-labeled VQA instructions paired with 3D CT scans, with step-aligned rationales and cross-modal alignments along the trajectory from findings to impression to pathology, enabling evaluation of both answer accuracy and reasoning consistency. We further propose TumorChain, a multimodal interleaved reasoning framework that tightly couples 3D imaging encoders, clinical text understanding, and organ-level vision-language alignment. Through cross-modal alignment and iterative interleaved causal reasoning, TumorChain grounds visual evidence, aggregates conclusions, and issues pathology predictions after multiple rounds of self-refinement, improving traceability and reducing hallucination risk. Experiments show consistent improvements over strong baselines in lesion detection, impression generation, and pathology classification, and demonstrate strong generalization on the DeepTumorVQA benchmark. These results highlight the potential of multimodal reasoning for reliable and interpretable tumor analysis in clinical practice. Detailed information about our project can be found on our project homepage atthis https URL.
  </details>
