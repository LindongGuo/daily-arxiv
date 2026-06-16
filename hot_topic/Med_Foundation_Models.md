# 🔍 Med_Foundation_Models Papers · 2026-06-15

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Temporally Consistent and Controllable Video Generation of 2D Cine CMR via Latent Space Motion Modeling](https://arxiv.org/abs/2606.14759)**  `arXiv:2606.14759`  `cs.CV` `cs.AI`  
  _Yiheng Cao, Gustavo Andrade-Miranda, Jiatian Zhang, Guillaume Sallé, Xin Gao_
  <details open><summary>Abstract</summary>
  Cine cardiac magnetic resonance is the gold standard for assessing cardiac function, but the scarcity of public datasets limits the development of advanced data-driven models. To address this limitation, we propose a generative method for synthesizing temporally coherent and anatomically consistent cardiac sequences. Our text-to-video framework decouples cardiac spatial structure from temporal motion. First, a fine-tuned diffusion model synthesizes an initial frame from a clinical text prompt, controlling anatomical features. Then, a latent flow model conditioned on a cardiac phase embedding generates the complete cardiac motion, ensuring spatial consistency and temporal control. Our model generates anatomically and pathologically diverse sequences with high temporal coherence and strong fidelity to input prompts, achieving a FID of 31.68 for image realism and a CLIP score of 31.04 for text-image alignment. These experimental results highlight its potential to produce high-fidelity, on-demand medical data, offering a scalable solution to data scarcity.
  </details>

- **[Detect Before You Leap: Mirage Detection in Vision-Language Models](https://arxiv.org/abs/2606.00435)**  `arXiv:2606.00435`  `cs.CV` `cs.AI`  
  _Sayeed Shafayet Chowdhury, Md. Shaown Miah, S. M. Taiabul Haque, Syed Ishtiaque Ahmed_
  <details open><summary>Abstract</summary>
  Vision-language models (VLMs) can produce confident visual answers even when the required visual evidence is missing, blank, or unrelated to the question. This failure mode, recently described as mirage (mirage2026), is especially concerning in medical and document VQA, where a plausible but visually ungrounded answer may be mistaken for image-based evidence. We study the complementary problem of pre-release mirage detection: given an image-question pair, determine whether the VLM should answer or abstain before generation. To that end, we propose a novel model-agnostic Text-Conditioned Layer-wise Internal Alignment (TC-LIA) method that probes patch-token representations across the layers of a CLIP ViT-H/14 vision encoder. The key idea is to project layer-wise image patch tokens into the final CLIP embedding space and measure their similarity with the question embedding, thereby tracking whether question-relevant visual evidence emerges across vision layers. TC-LIA summarizes this alignment trajectory using final image-text cosine similarity, late-layer top-k patch-text alignment, early-to-late gain, and layer-wise slope. These features are combined with pixel-statistic based blank/noise detection, zero-shot domain routing, and structured VLM self-assessment in an ensemble. Across five VQA domains with related, unrelated-real, and blank/noise inputs, and across twelve VLM backbones, Qwen2.5-VL-32B achieves the highest three-class detection accuracy of 94.7% with a 3.0% mirage rate, while Qwen2.5-VL-72B achieves 94.6% accuracy with a lower 2.8% mirage rate. Baseline mirage rates span 21.7-66.6%.
  </details>
