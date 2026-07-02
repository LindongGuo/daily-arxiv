# 🔍 Med_Foundation_Models Papers · 2026-07-01

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[TRCGL-Net: A Long-Tailed Multi-Label Chest X-Ray Classification Framework with Generative Data Augmentation and Label Co-Occurrence Modeling](https://arxiv.org/abs/2607.00975)**  `arXiv:2607.00975`  `cs.CV` `cs.AI`  
  _Tong Shao, Hongshun Ling, Li Zhang, Jinjing Wu, Junke Wang, Yuan Gao, et al._
  <details open><summary>Abstract</summary>
  Chest X-ray multi-label classification is a core task in intelligent medical imaging diagnosis. However, real clinical data often exhibit extreme long-tailed distributions, leading to degraded performance on rare diseases in tail classes. This issue is not only driven by data scarcity but also by two intrinsic factors:1) attenuation of tail-class lesion representations under complex anatomical backgrounds, and 2) dominance of head classes in modeling label co-occurrence relationships. To address these challenges, we propose TRCGL-Net. First, a learnable text-guided conditional diffusion model is employed to generate high-quality tail-class chest X-ray image samples under disease semantic constraints, improving data diversity and realism of rare disease patterns while alleviating class imbalance and preserving pathology-consistentthis http URL, a channel reweighting mechanism is introduced to perform feature recalibration by emphasizing disease-relevant feature channels, thereby improving feature discriminability under long-tailed distributions.A class-aware attention mechanism is further applied to generate class-specific attention maps, enabling the model to localize disease-relevant regions and focus on fine-grained lesionthis http URL, a graph convolution network based on label co occurrence is introduced to establish an information propagation mechanism among categories. Experiments on the PadChest dataset show that the proposed method achieves a tail-class mAP of 0.4904, an overall mAP of 0.4408, and an mAUC of 0.8989, outperforming state-of-the-art methods. TRCGL-Net effectively improves recognition performance for rare diseases under long-tailed distributions and mitigates the impact of extreme class imbalance in chest X-ray multi-label classification.
  </details>

- **[Controllable Diffusion-Based Lesion Inpainting for Scalable Histopathology Data Augmentation](https://arxiv.org/abs/2601.08127)**  `arXiv:2601.08127`  `cs.CV` `cs.AI`  
  _Mohamad Koohi-Moghadam, Mohammad-Ali Nikouei Mahani, Rex K.H. Au-Yeung, Raymond Yu O, Monalyn Marabi, Piyapharom Intarawichian, et al._
  <details open><summary>Abstract</summary>
  Expert-annotated training data remains the critical bottleneck for AI in histopathology, particularly for rare pathologies where even dozens of cases may be unavailable. While data augmentation offers a solution, existing methods fail to generate sufficiently realistic lesion morphologies that preserve tissue-specific architectures. Here we present PathoGen, a diffusion-based generative model enabling controllable, high-fidelity lesion inpainting into benign histopathology images. We validate PathoGen across four datasets representing kidney, skin, breast, and prostate pathology. Quantitative assessment confirms PathoGen outperforms state-of-the-art baselines in image fidelity and distributional similarity. Evaluation by six expert pathologists revealed that synthetic images by PathoGen were only marginally distinguished from real tissue image slightly above chance (57.75% accuracy), demonstrating strong perceptual realism of PathoGen-generated lesions. PathoGen achieved the highest win rate (35.4%) when pathologists ranked generation quality against all baselines. Crucially, augmenting training sets with PathoGen-synthesized lesions improves segmentation Dice scores by up to 0.18 compared to traditional augmentations, with maximum benefit in data-scarce regimes. By simultaneously generating realistic morphology and pixel-level annotations, PathoGen effectively addresses both data scarcity and annotation cost, two critical bottlenecks in computational pathology development.
  </details>
