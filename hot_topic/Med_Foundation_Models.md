# 🔍 Med_Foundation_Models Papers · 2026-06-01

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Detect Before You Leap: Mirage Detection in Vision-Language Models](https://arxiv.org/abs/2606.00435)**  `arXiv:2606.00435`  `cs.CV` `cs.AI`  
  _Sayeed Shafayet Chowdhury, Md. Shaown Miah_
  <details open><summary>Abstract</summary>
  Vision-language models (VLMs) can produce confident visual answers even when the required visual evidence is missing, blank, or unrelated to the question. This failure mode, known as mirage (Asadi et al. 2026), is especially concerning in medical and document visual question answering, where plausible but visually ungrounded responses may be mistaken for image-based evidence. We study pre-release mirage detection: given an image-question pair, the goal is to determine whether a VLM should answer or abstain before producing a response. We propose Text-Conditioned Layer-wise Internal Alignment (TC-LIA), a model-agnostic method that probes patch-token representations across the layers of a CLIP ViT-H/14 vision encoder. TC-LIA projects layer-wise image patch tokens into the final CLIP embedding space and measures their similarity to the question embedding, allowing the method to track whether question-relevant visual evidence emerges across vision layers. The resulting alignment trajectory is summarized using final image-text cosine similarity, late-layer top-k patch-text alignment, early-to-late gain, and layer-wise slope. These features are combined with pixel-statistic blank/noise detection, zero-shot domain routing, and structured VLM self-assessment in an ensemble. Across five VQA domains, three input conditions, and twelve VLM backbones, the best systems achieve approximately 94.6-94.7% three-class detection accuracy with mirage rates below 3%, while baseline mirage rates range from 21.7% to 66.6%.
  </details>

- **[Task-Aligned Self-Supervised Learning for Medical Image Analysis: A Systematic Review and Practical Design Guidelines](https://arxiv.org/abs/2605.23995)**  `arXiv:2605.23995`  `cs.CV` `cs.AI`  
  _Chathura Wimalasiri_
  <details open><summary>Abstract</summary>
  Self-supervised learning (SSL) has emerged as a promising paradigm for addressing the annotation bottleneck in medical imaging by learning representations from unlabeled data. However, its effectiveness depends heavily on the design of the pretext task and its alignment with the downstream clinical-objectives. We present a systematic, task-oriented review of SSL in medical imaging, examining how different pretext-task formulations influence performance across classification, segmentation, detection, and other tasks. Following PRISMA guidelines, we analyze 75 studies published between 2017 and 2025 and organize them into four paradigms: contrastive, non-contrastive and predictive, generative and reconstruction-based, and hybrid learning. Rather than cataloguing methods by architecture, we map each paradigm to the downstream objectives it best supports. Our analysis shows there is no universally optimal SSL strategy; instead, performance is governed by the alignment between the pretext task, the imaging modality, and the target task. Contrastive methods learn global discriminative features and align well with classification, but may overlook subtle pathological patterns. Generative and spatial prediction-based approaches better preserve local anatomical structure, making them more suitable for segmentation and other dense prediction tasks, while hybrid methods offer the most balanced performance. We further show that modality-specific design is critical and that SSL provides its greatest benefit in low-label and few-shot regimes. Finally, we distill these findings into practical design guidelines and outline open challenges, including pathology-aware pretext task design, resource-efficient training for high-dimensional data, and standardized evaluation protocols. This work offers practical guidance for designing more effective and clinically relevant SSL frameworks in medical imaging.
  </details>

- **[PathAR: Structure-First Autoregressive Synthesis of Multimodal Pathology Images](https://arxiv.org/abs/2606.01543)**  `arXiv:2606.01543`  `cs.CV`  
  _Yuan Zhang, Jiahao Xia, Junzhang Huang, Meng Wang, Feng Chen, Guanyu Yang, et al._
  <details open><summary>Abstract</summary>
  Data scarcity in multimodal pathology motivates unified generative models that synthesize modality-specific appearance while preserving anatomically coherent structure. Although modalities differ in appearance statistics, morphological structures such as cellular topology and tissue boundaries are largely preserved across acquisition protocols. However, existing methods often model these factors within a homogeneous token stream, implicitly coupling structure with appearance and weakening structural controllability under modality shifts. To address this, we propose pathology Autorgressive modeling (PathAR), a structure-first autoregressive synthesis framework that explicitly factorizes structure and appearance for modality-label-conditioned pathologythis http URLemploys a dual vector quantization (Dual-VQ) tokenizer to decompose samples into mask-grounded structure and appearance tokens, and an interleaved autoregressive (IAR) transformer with asymmetric attention visibility to enforce structure-to-appearance dependence. PathAR stabilizes morphology under heterogeneous modality-specific appearances and enables spatially aligned image--mask pair generation. Extensive experiments show that PathAR improves structural consistency and modality fidelity over baselines, maintains sample diversity, supports downstream segmentation in data-scarce regimes, and demonstrates extensibility to finer-grained intra-modality organ-label variation.
  </details>
