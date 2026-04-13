# 🔍 Med_Foundation_Models Papers · 2026-04-12

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[M-IDoL: Information Decomposition for Modality-Specific and Diverse Representation Learning in Medical Foundation Model](https://arxiv.org/abs/2604.08936)**  `arXiv:2604.08936`  `cs.CV`  
  _Yihang Liu, Ying Wen, Jiaxiong Yang, Longzhen Yang, Lianghua He, Heng Tao Shen_
  <details open><summary>Abstract</summary>
  Medical foundation models (MFMs) aim to learn universal representations from multimodal medical images that can generalize effectively to diverse downstream clinical tasks. However, most existing MFMs suffer from information ambiguity that blend multimodal representations in a single embedding space, leading to the degradation of modality specificity and diversity. In this paper, we propose M-IDoL, a self-supervised \underline{\textit{M}}FM that introduces Information Decomposition for multimodal representation Learning via two objectives: i) maximize inter-modality entropy by dispersing multimodal representation into separable Mixture-of-Experts (MoE) subspaces to achieve representation specificity across modalities; and ii) minimize intra-modality uncertainty by performing fine-grained semantic discrimination within each MoE subspace to enrich representation diversity per modality. By pre-training on 1.15 million medical images, M-IDoL i) delivers superior generalization across 21 downstream clinical tasks, outperforming 20 foundation models on five imaging modalities (e.g., X-ray, fundus, OCT, dermoscopy and pathology), and ii) learns modality-specific and diverse representations, showing clearer separation of feature cluster across modalities and finer-grained feature discrimination within each modality.
  </details>

- **[Plug-and-Play Logit Fusion for Heterogeneous Pathology Foundation Models](https://arxiv.org/abs/2604.07779)**  `arXiv:2604.07779`  `cs.CV`  
  _Gexin Huang, Anqi Li, Yusheng Tan, Beidi Zhao, Gang Wang, Zu-Hua Gao, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) have become central to computational histopathology, offering strong transfer performance across a wide range of diagnostic and prognostic tasks. The rapid proliferation of pathology foundation models creates a model-selection bottleneck: no single model is uniformly best, yet exhaustively adapting and validating many candidates for each downstream endpoint is prohibitively expensive. We address this challenge with a lightweight and novel model fusion strategy, LogitProd, which treats independently trained FM-based predictors as fixed experts and learns sample-adaptive fusion weights over their slide-level outputs. The fusion operates purely on logits, requiring no encoder retraining and no feature-space alignment across heterogeneous backbones. We further provide a theoretical analysis showing that the optimal weighted product fusion is guaranteed to perform at least as well as the best individual expert under the training objective. We systematically evaluate LogitProd on \textbf{22} benchmarks spanning WSI-level classification, tile-level classification, gene mutation prediction, and discrete-time survival modeling. LogitProd ranks first on 20/22 tasks and improves the average performance across all tasks by ~3% over the strongest single expert. LogitProd enables practitioners to upgrade heterogeneous FM-based pipelines in a plug-and-play manner, achieving multi-expert gains with $\sim$12$\times$ lower training cost than feature-fusion alternatives.
  </details>

- **[Zero-Shot Generative De-identification: Inversion-Free Flow for Privacy-Preserving Skin Image Analysis](https://arxiv.org/abs/2602.00821)**  `arXiv:2602.00821`  `cs.CV`  
  _Konstantinos Moutselos, Ilias Maglogiannis_
  <details open><summary>Abstract</summary>
  The secure analysis of dermatological images in clinical environments is fundamentally restricted by the critical trade-off between patient privacy and the preservation of diagnostic fidelity. Traditional de-identification techniques often degrade essential pathological markers, while state-of-the-art generative approaches typically require computationally intensive inversion processes or extensive task-specific fine-tuning, limiting their feasibility for real-time deployment. This study introduces a zero-shot generative de-identification framework that utilizes an inversion-free pipeline for privacy-preserving medical image analysis. By leveraging Rectified Flow Transformers (FlowEdit), the proposed method achieves high-fidelity identity transformation in less than 20 seconds without requiring pathology-specific training or labeled datasets. We introduce a novel "segment-by-synthesis" mechanism that generates counterfactual "healthy" and "pathological" digital twin pairs to isolate clinical signals from biometric identifiers in a zero-shot manner. Our approach specifically utilizes the CIELAB color space to decouple erythema-related pathological signals from semantic noise and individual skin characteristics. Pilot validation on high-resolution clinical samples demonstrates robust stability in preserving pathological features, achieving an Intersection over Union (IoU) stability exceeding 0.67, while ensuring rigorous de-identification. These results suggest that the proposed zero-shot, inversion-free approach provides a scalable and efficient solution for secure data sharing and collaborative biomedical research, bypassing the need for large-scale annotated medical datasets while aligning with data protection standards.
  </details>
