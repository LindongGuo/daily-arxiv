# 🔍 Med_Foundation_Models Papers · 2026-07-27

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Robustifying pathology foundation models via fine-tuning](https://arxiv.org/abs/2607.22861)**  `arXiv:2607.22861`  `cs.CV` `cs.AI`  
  _Alexandre Filiot, Oskar Thaeter, Benoit Schmauch, Lionel Guillou_
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) produce powerful tile-level representations which remain sensitive to scanner and staining variability, undermining deployment across laboratories. We develop a novel fine-tuning recipe that improves the robustness of pathology FMs to acquisition factors. Applied to ten different FMs, our fine-tuning strategy consistently improves robustness for every model as well as downstream performance, with no observed trade-off. On average, it raises the PathoROB robustness index by 23% (from 0.72 to 0.87) and increases the overall cross-benchmark performance by 43% on Patho-Bench, HEST and THUNDER combined, with individual gains reaching up to 72% in robustness (Phikon-v2) and 76% in performance (Midnight-12k). We publicly release the fine-tuned versions of Phikon-v2 (Phaet) and Midnight-12k (Mascaret) atthis https URL.
  </details>

- **[Task-Aligned Self-Supervised Learning for Medical Image Analysis: A Task-Oriented Review with Practical Design Guidelines](https://arxiv.org/abs/2605.23995)**  `arXiv:2605.23995`  `cs.CV` `cs.AI`  
  _Chathura Wimalasiri, Yuchong Yao, Kishor Nandakishor, Marimuthu Palaniswami_
  <details open><summary>Abstract</summary>
  Self-supervised learning (SSL) is increasingly used in medical image analysis to reduce dependence on costly expert annotations by learning transferable representations from unlabeled data. However, SSL performance depends not only on model architecture but also on whether the self-supervised objective preserves the information required by the downstream clinical task. This review presents a task-oriented synthesis of SSL methods for medical imaging, focusing on how the design of the self-supervised objective interacts with imaging modality, label availability, and downstream performance. We analyze $78$ studies published from 2017 to 2025 and organize them into four paradigms: contrastive, non-contrastive and predictive, generative and reconstruction-based, and hybrid learning. Rather than cataloging methods chronologically, we examine how these paradigms support classification, segmentation, detection, reconstruction, and regression. The evidence suggests that effectiveness is governed by the match among objective, modality, and downstream task rather than by any single strategy. Contrastive objectives favor global discriminative representations suited to classification but may underrepresent localized pathology, whereas spatial-prediction, masked-modeling, and reconstruction objectives better preserve anatomical structure for segmentation and dense prediction. Critically, misaligned objectives can cause negative transfer through shortcut learning on acquisition signatures or augmentation that erases diagnostic signal rather than merely weaker gains. SSL is most beneficial in low-label regimes, but its effectiveness depends on modality-aware augmentation, pathology-preserving corruption, and clinically meaningful evaluation. We conclude with practical design guidelines and open challenges for clinically aligned SSL.
  </details>

- **[PathSelect: Sequential Token Selection for Whole Slide Pathology](https://arxiv.org/abs/2607.23631)**  `arXiv:2607.23631`  `cs.CV`  
  _Jingzhi Chen, Landi He, Zehong Chen, Peihang Wu, Lijian Xu_
  <details open><summary>Abstract</summary>
  Gigapixel Whole-Slide Images (WSIs) present a fundamental computational bottleneck for vision-language models (VLMs) due to extreme sequence lengths. Existing approaches predominantly rely on spatial sampling or training-free pruning, which risk diluting weak but informative signals, leading to the loss of critical diagnostic evidence due to the spatially diffuse nature of pathological cues. We reformulate WSI token pruning as a sequential selection process, enabling the model to autonomously learn an optimal routing strategy rather than relying on static heuristics. We herein propose a decoupled routing framework integrated as an active plugin into the fully pre-trained SlideChat base model, leaving both the slide encoder and large language model frozen. To provide continuous gradients for the non-differentiable pruning operation during training, we introduce PathSelect. PathSelect employs a variance-preserving noise gate to modulate each patch's information flow via a differentiable Soft Top-K operator, paired with a diagonal-attention Denoiser that recovers the perturbed representations without semantic leakage. At inference, the PathSelect module is entirely detached. Relying solely on the trained Scorer, a deterministic Hard Top-K operator executes adaptive, data-dependent trajectory termination, significantly accelerating downstream generative processing with exceptionally low sequential token selection latency. Driven by an empirical average of only 44.86 tokens under a maximum constraint of K = 128, our framework achieves 74.00% overall accuracy on SlideBench (TCGA), representing an approximate 36.6x spatial token reduction relative to the uncompressed baseline average while consistently outperforming sampling-based counterparts.
  </details>
