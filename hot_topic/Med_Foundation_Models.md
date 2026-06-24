# 🔍 Med_Foundation_Models Papers · 2026-06-23

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Jolia: Concept-Level Vision-Language Alignment for 3D CT Contrastive Learning](https://arxiv.org/abs/2606.24570)**  `arXiv:2606.24570`  `cs.CV`  
  _Julien Khlaut, Charles Corbière, Baptiste Callard, Amaury Prat, Leo Butsanets, Antoine Saporta, et al._
  <details open><summary>Abstract</summary>
  Vision-language contrastive pretraining has become the dominant recipe for 3D medical foundation models, leveraging the large volumes of paired scans and reports produced in clinical practice. However, medical images usually span dozens of organs, and radiological reports are much longer than typical natural image captions and are composed of multiple structured sections. CLIP-style pretraining compresses this structure by encoding each modality into a single global token, at the risk of losing important details. We introduce ConQuer (Concept Queries), an image-text pretraining method that augments CLIP's global alignment with a set of localized alignments, one per concept. ConQuer splits the report into concept-specific sections and learns cross-attention queries that pool the matching image features without using any segmentation mask or spatial supervision. Contrastive learning is then applied independently for each concept. Concepts can be any unit of semantic localization; here, they are anatomical regions, one query per organ or gross body region. As a byproduct, each query learns attention maps focused on its concept, providing built-in spatial interpretability. We use ConQuer to train Jolia, a 3D CT foundation model on chest and abdominal CT. Jolia consistently outperforms a CLIP baseline on findings classification, report generation, and cross-center transfer, and sets a new state of the art across multiple public benchmarks. Jolia's weights will be released upon acceptance.
  </details>

- **[Do Foundation Models See Biology? Evaluating Attention Coherence with Spatial Transcriptomics in Glioblastoma](https://arxiv.org/abs/2606.04764)**  `arXiv:2606.04764`  `cs.CV`  
  _Dilakshan Srikanthan, Amoon Jamzad, Paul Wilson, Nooshin Maghsoodi, Robert Policelli, Gabor Fichtinger, et al._
  <details open><summary>Abstract</summary>
  Whether attention maps from pathology foundation models capture genuine biology remains unknown, yet this question is critical for clinical trust and regulatory approval. We propose a spatial transcriptomics-based framework for orthogonal, hypothesis-free evaluation of attention and apply it to five pathology foundation models (CONCH v1.5, UNI v2, Virchow2, GigaPath, H-Optimus-1) and a ResNet50 baseline. Using attention-based multiple instance learning, we train single-task and multi-task models to predict five molecular alterations in glioblastoma on the CPTAC cohort, validate on an independent TCGA cohort, and evaluate biological coherence of attention maps against 87 transcriptional signatures using co-registered Visium spatial transcriptomics data from 18 samples. Internally, no single encoder dominates across all tasks, and external validation inverts internal performance rankings. Attention maps show a five-fold enrichment gradient from pathways (Cohen's d=0.329) to individual genes (d=0.055), indicating that attention captures emergent multi-gene transcriptional programs rather than individual molecular events. Spatially smooth attention maps do not imply biological coherence, and different encoders attend to distinct biological compartments. Our framework provides objective, quantitative assessment of what foundation models learn from histopathology, moving the field beyond qualitative saliency map review.
  </details>

- **[MedP-CLIP: Medical CLIP with Region-Aware Prompt Integration](https://arxiv.org/abs/2604.11197)**  `arXiv:2604.11197`  `cs.CV`  
  _Jiahui Peng, He Yao, Jingwen Li, Yanzhou Su, Sibo Ju, Yujie Lu, et al._
  <details open><summary>Abstract</summary>
  Contrastive Language-Image Pre-training (CLIP) has demonstrated outstanding performance in global image understanding and zero-shot transfer through large-scale text-image alignment. However, the core of medical image analysis often lies in the fine-grained understanding of specific anatomical structures or lesion regions. Therefore, precisely comprehending region-of-interest (RoI) information provided by medical professionals or perception models becomes crucial. To address this need, we propose MedP-CLIP, a region-aware medical vision-language model (VLM). MedP-CLIP innovatively integrates medical prior knowledge and designs a feature-level region prompt integration mechanism, enabling it to flexibly respond to various prompt forms (e.g., points, bounding boxes, masks) while maintaining global contextual awareness when focusing on local regions. We pre-train the model on a meticulously constructed large-scale dataset (containing over 6.4 million medical images and 97.3 million region-level annotations), equipping it with cross-disease and cross-modality fine-grained spatial semantic understanding capabilities. Experiments demonstrate that MedP-CLIP significantly outperforms baseline methods in various medical tasks, including zero-shot recognition, interactive segmentation, and empowering multimodal large language models. This model provides a scalable, plug-and-play visual backbone for medical AI, combining holistic image understanding with precise regional analysis.
  </details>
