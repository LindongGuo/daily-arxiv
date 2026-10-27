# 🔍 Med_Foundation_Models Papers · 2026-10-26

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Learning Pathology-Sensitive Representations for Unsupervised Retinal OCT Anomaly Detection](https://arxiv.org/abs/2610.33143)**  `arXiv:2610.33143`  `cs.CV` `cs.LG`  
  _Tania Haghighi, Sina Gholami, Behafarin Emam, Jennifer I Lim, Theodore Leng, Atalie C Thompson, et al._
  <details open><summary>Abstract</summary>
  Deep learning approaches for retinal optical coherence tomography (OCT) predominantly rely on predefined disease categories, limiting their ability to detect rare or previously unseen abnormalities. While visual foundation models provide transferable representations, their effectiveness in identifying pathological deviations from normal retinal anatomy remains insufficiently understood. In this work, we introduce an unsupervised framework for retinal OCT anomaly detection and localization that adapts pretrained visual representations to normal retinal anatomy through anatomy-aware reconstruction and contrastive triplet learning guided by synthetic structural perturbations, without requiring disease-specific annotations. We systematically investigate the influence of pretraining strategies, anatomy-aware representation adaptation, and anomaly scoring mechanisms on the detection and localization of unseen retinal abnormalities. Our findings demonstrate that adapting pretrained representations to normal retinal structure improves anomaly sensitivity, while pixel-space reconstruction errors and feature-space deviations provide complementary signals for identifying pathological changes. These findings underscore the importance of anatomy-aware representation learning and offer insights into developing generalizable retinal anomaly detection frameworks beyond predefined disease categories.
  </details>

- **[MOSAIC: Towards a Universal Latent Space for Computational Pathology Foundation Models](https://arxiv.org/abs/2610.33059)**  `arXiv:2610.33059`  `cs.CV` `cs.AI`  
  _Dibaloke Chanda, Praveen Madiraju_
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) differ substantially in architecture, pretraining objective, training data and representation dimensionality, yet it remains unclear whether they learn fundamentally different feature spaces or alternative coordinate systems of a shared underlying representation. We present MOSAIC, a systematic study of latent-space similarity, alignment and interoperability across $12$ patch-level and $6$ slide-level PFMs. We first quantify representational agreement using complementary similarity measures and analyze how architecture, pretraining objective, network depth and magnification influence latent geometry. We then evaluate multiple alignment strategies for mapping independently learned representations into a common latent space. The resulting representations are evaluated through cross-model agreement, retrieval, geometry preservation, and downstream multiple-instance learning across molecular and morphological prediction tasks. MOSAIC provides a unified framework for studying whether heterogeneous PFMs can move beyond representational similarity toward a shared and functionally transferable pathology representation space. Our code, benchmarks and additional results are available atthis https URL.
  </details>

- **[Do Words Matter? What Text Contributes to Few and Full-Shot Vision-Language Anomaly Detection](https://arxiv.org/abs/2610.34610)**  `arXiv:2610.34610`  `cs.CV`  
  _Arda Baris Basaran, Mesut Ceylan, Elgar Fleisch, Filipe Barata_
  <details open><summary>Abstract</summary>
  Vision-language anomaly detectors describe normal and abnormal appearance with text, and their gains are commonly credited to the semantic content of these descriptions. This attribution is plausible in the zero-shot setting, but few- and full-shot detectors interpose a trained visual adapter, and in that setting it has not been isolated. Changing a description changes both its meaning and its geometry, so accuracy comparisons cannot separate the two. We ask what a fixed pair of text embeddings, or anchors, contributes to such a detector: semantic content, effective scale, or joint anchor geometry. For a single anchor pair, the answer is effective scale alone. The score reads the anchors only through their difference, and a trained adapter can rotate to follow any replacement direction, leaving that direction, and with it the linguistic content, unidentifiable. We prove that replacement anchors with the same difference-vector length permit exactly the same probability maps and attainable losses. Across seven medical datasets, three vision backbones, both supervision regimes, and three adapter families, scale-matched random and orthogonal anchors track correct prompts; breaking the scale match opens a gap that restoring it closes without text. The same pattern holds in MVFA and when MadCLIP's learned prompts are replaced by a text-free learned scale. When one adapter serves many categories, the answer expands to their joint arrangement. Rotating all category axes together changes nothing, as predicted. For the tested CLIP prompts, these axes are nearly collinear, and meaning-free rotations that spread them apart improve performance on both industrial benchmarks. Even under frozen zero-shot transfer, a random anchor frame transfers as well as the prompt frame: coordinate consistency, not meaning. What these detectors read from their prompts is scale and arrangement, not semantic content.
  </details>
