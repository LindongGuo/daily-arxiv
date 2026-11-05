# 🔍 Med_Foundation_Models Papers · 2026-11-04

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Multimodal Fusion Methods for Whole-Slide Images and Clinical Data in Inflammatory Bowel Disease](https://arxiv.org/abs/2611.05579)**  `arXiv:2611.05579`  `cs.CV` `cs.AI` `cs.LG`  
  _Ankana Banerjee, Mark van der Giezen, Ole Gunnar Aasprong, Emiel A. M. Janssen, Øyvind Steinsbø, Tore Grimstad, et al._
  <details open><summary>Abstract</summary>
  Multimodal AI fusion of histology and clinical data is an active research area in computational pathology, but fusion methods are rarely compared under identical conditions and across different clinical endpoints. We present a modular framework in which slide-level embeddings, obtained by training an attention-based aggregator over patch embeddings from a frozen foundation model, and per-visit clinical embeddings are fed into 15 interchangeable fusion methods with a shared output dimension and prediction head (except decision-level methods). Using a prospective cohort of newly diagnosed inflammatory bowel disease patients, we predicted STRIDE-II-aligned remission outcomes from baseline or follow-up visits. The best fusion method reached macro-F1 of 0.57-0.75, outperforming both single-modality models in four of six scenarios, and differed by outcome and input. Image reliance, the drop in balanced accuracy when the slide embedding is removed, tended to follow the remission type - highest for histological and lowest for endoscopic remission; methods with similar accuracy relied on the slide to very different degrees.
  </details>

- **[Agent-Driven Generative Priors for Pathology Image Synthesis and Segmentation](https://arxiv.org/abs/2611.06701)**  `arXiv:2611.06701`  `cs.CV`  
  _Sicheng Yang, Rui Tang, Haipeng Zhou, Hongqiu Wang, Zhaohu Xing, Jianda Ma, et al._
  <details open><summary>Abstract</summary>
  Deep learning methods for pathology are constrained by the limited availability and high cost of large-scale pixel-level annotations. Synthetic data can alleviate this limitation, but existing pipelines often lack reliable quality control and remain weakly connected to downstream analysis. To address these issues, we propose a three-stage framework that integrates automated data screening, generative representation learning, and efficient adaptation to downstream tasks. First, we develop a pathology agent system to assess image quality and filter samples, resulting in TCGA-200K, a dataset containing 217,030 pathology patches selected from the public TCGA repository. Second, we train a generative model on the screened data. In addition to image synthesis, its backbone learns structural and semantic representations that can be transferred to downstream tasks. Third, we adapt the pretrained generative backbone to semantic segmentation using a lightweight task-specific head. We further introduce PathSeg-380K, a semantic segmentation dataset with expert annotations for approximately 380,000 cells across 12 cell types. Experiments on multiple pathology datasets show that the proposed framework achieves state-of-the-art segmentation performance. Our code is publicly available atthis https URL.
  </details>

- **[PathoS2VD: From 2D Histopathology to Pseudo Z-Stack Representations](https://arxiv.org/abs/2611.05974)**  `arXiv:2611.05974`  `cs.CV`  
  _Jiamu Wang, Keunho Byeon, Ji-Uk Kim, Jin Tae Kwak, Heounjeong Go_
  <details open><summary>Abstract</summary>
  For decades, diagnostic pathology has relied on thin two-dimensional (2D) tissue sections, despite biological tissues exhibiting inherently three-dimensional (3D) morphological organization. Because a single section captures only one focal plane, important morphological cues along the z-axis are inevitably discarded, limiting tissue representation for both human interpretation and computational analysis. In this work, we propose a generative framework that learns z-axis morphological priors from pathology z-stack data, offering a cost-effective alternative to dedicated volumetric imaging, and transfers this knowledge to conventional single-plane histopathology. Specifically, an image-to-video (I2V) latent diffusion model (LDM) is trained to synthesize a pseudo z-stack from a single 2D image, capturing plausible morphological variations across adjacent focal planes rather than reconstructing physical tissue volumes. To enable deployment on large-scale clinical datasets without native z-stack acquisition, we further introduce a prior-preserving mixture fine-tuning strategy that adapts the model to new domains while retaining the learned z-axis morphological prior. Extensive experiments demonstrate that the synthesized pseudo z-stacks exhibit realistic cross-plane morphological continuity and consistently improve downstream prostate cancer classification compared with conventional 2D representations. Our results suggest that learning transferable z-axis priors from limited z-stack data provides a practical way to enrich routine pathology images with complementary morphological information. Code:this https URL.
  </details>
