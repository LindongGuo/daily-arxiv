# 🔍 Med_Foundation_Models Papers · 2026-07-19

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[CompDiff: Hierarchical Compositional Diffusion for Fair and Zero-Shot Intersectional Medical Image Generation](https://arxiv.org/abs/2603.16551)**  `arXiv:2603.16551`  `cs.CV` `cs.AI`  
  _Mahmoud Ibrahim, Bart Elen, Chang Sun, Gokhan Ertaylan, Michel Dumontier_
  <details open><summary>Abstract</summary>
  Generative models are increasingly used to augment medical imaging datasets for fairer AI, yet a key assumption often goes unexamined: that generators produce equally high-quality images across demographic groups. Models trained on imbalanced data inherit these imbalances, degrading synthesis for rare subgroups and struggling with intersections absent from training: the imbalanced generator problem. Remedies such as loss reweighting operate at the optimization level and provide limited benefit when training signal is scarce or absent. We propose CompDiff, a hierarchical compositional diffusion framework that addresses this at the representation level. A dedicated Hierarchical Conditioner Network (HCN) decomposes demographic conditioning into single-attribute, pairwise, and composed representations, producing a demographic token concatenated with CLIP embeddings as cross-attention context. This structured factorization encourages parameter sharing across subgroups and supports compositional generalization to rare or unseen intersections. On chest X-rays (MIMIC-CXR) and fundus images (FairGenMed), CompDiff compares favorably against standard fine-tuning and FairDiffusion across image quality (FID 64.3 vs. 75.1), subgroup equity (ES-FID), and zero-shot intersectional generalization (up to 21% FID improvement on held-out intersections). Downstream classifiers trained on CompDiff data show improved AUROC and reduced demographic bias, suggesting that the architectural design of demographic conditioning is an important and underexplored factor in fair medical image generation. Code:this https URL.
  </details>

- **[When Can Test-Time Adaptation Help Zero-Shot CT Vision-Language Models?](https://arxiv.org/abs/2607.15556)**  `arXiv:2607.15556`  `cs.CV`  
  _Ailar Mahdizadeh, Puria Azadi Moghadam, Xiangteng He, Leonid Sigal_
  <details open><summary>Abstract</summary>
  3D CT vision-language models (VLMs) classify abnormalities from text prompts in a zero-shot manner, enabling cross-institution deployment where labels are scarce and clinical tasks shift faster than supervised models can be retrained. A real CT scan, however, typically contains several co-occurring abnormalities, and the reliability of zero-shot multi-label prediction under distribution shift remains poorly understood. Test-time adaptation (TTA) updates a model on unlabeled target scans without source data or target annotations, yet existing TTA methods target multi-class softmax prediction on natural images or 2D medical segmentation, and none addresses unsupervised multi-label adaptation for zero-shot 3D CT VLMs. We study when TTA helps zero-shot 3D CT VLMs. A controlled diagnostic analysis shows that TTA is conditional: the volumetric input must preserve the encoder's depth structure, and the base representation must transfer to the target cohort, with depth reduction alone lowering internal AUROC by more than 0.12. We then focus on the regime where the base model already separates present from absent abnormalities. We introduce CARVE (Cardinality-Aware Retained-View Entropy), the first TTA method for this setting. CARVE estimates a sample-specific positive-label cardinality $\hat{k}$, optimizes a top-$\hat{k}$ objective to preserve co-occurring abnormalities, and performs memory-efficient multi-view adaptation by scoring weak 3D views without gradients before updating on a retained subset. Across contrastive CT-CLIP and anatomy-aware fVLM, CARVE provides the most consistent improvements across multi-label, three-class, and binary CT tasks when the base model is already discriminative. These results establish multi-label TTA for zero-shot 3D CT VLMs as a distinct problem and CARVE as a cardinality-aware solution.
  </details>
