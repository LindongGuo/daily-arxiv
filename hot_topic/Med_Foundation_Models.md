# 🔍 Med_Foundation_Models Papers · 2026-08-02

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Mitigating Class-Tail Undercoverage in Medical Vision-Language Models under Clinical Shift](https://arxiv.org/abs/2607.28696)**  `arXiv:2607.28696`  `cs.LG` `cs.CV`  
  _Mushir Akhtar, M. Tanveer_
  <details open><summary>Abstract</summary>
  Medical vision-language models (VLMs) can retain high observed marginal coverage after clinical shift while substantially under-covering an individual disease class. The affected class varies with acquisition protocol and backbone geometry, so source prevalence does not reliably reveal the failure. Existing localized and tail-aware conformal methods respectively adapt to test neighborhoods and source-frequency tails, leaving held-out class-wise coverage failure unmodeled. We introduce Class-Tail Adaptive Localized Conformal Deferral (CALCoDe), a post-hoc reliability layer for frozen medical VLMs. Cross-fitted validation predictions identify classes at risk of undercoverage, and a disjoint calibration split estimates their class-conditional tail thresholds. CALCoDe combines each protected threshold with a localized conformal threshold using a one-sided maximum. The resulting set contains every label admitted by the localized rule, with additional protection confined to validation-identified classes. An independently calibrated support audit defers cases with insufficient inlier support. Under exchangeability among accepted examples within each protected class, CALCoDe provides finite-sample coverage at the prespecified guard level and contains the corresponding localized conformal sets; coverage on shifted external cohorts is evaluated empirically. Among standard conformal baselines and recent VLM-specific conformal methods evaluated across two dermatology shifts (HAM10000 to ISIC 2019 and HAM10000 to PAD-UFES-20) and four frozen VLM backbones (BiomedCLIP, OpenAI CLIP ViT-B/32, PubMedCLIP ViT-B/32, and MedSigLIP-448), CALCoDe is the only approach whose observed marginal and worst-class accepted coverage both reach 0.95 in all eight settings. On HAM10000 to ISIC 2019, its average worst-class accepted coverage is 0.970, compared with 0.926 for sTACP and 0.864 for LCP-VLM.
  </details>

- **[VFAD: Variational Semantic Prompting Meets Frequency-Adaptive Representation Learning for Zero-Shot Anomaly Detection](https://arxiv.org/abs/2607.29370)**  `arXiv:2607.29370`  `cs.CV`  
  _Peng Chen, Kaige Li, Wei Wang, Mingbo Yang, Wenqiang Wang, Li Shen, et al._
  <details open><summary>Abstract</summary>
  Zero-shot anomaly detection (ZSAD) aims to detect and localize anomalies in unseen categories without access to target-specific training data. Although recent CLIP-based methods have demonstrated promising generalization through vision-language alignment, they remain limited in capturing diverse anomaly semantics and subtle local variations. To address these limitations, we propose VFAD, a unified framework that combines variational semantic prompting with frequency-adaptive representation learning. Specifically, we introduce a Variational Semantic Prompt Extractor (VSPE), which adaptively aggregates anomaly-relevant local semantics from dense patch tokens and regularizes them through a variational information bottleneck, thereby incorporating fine-grained visual cues and enabling more precise cross-modal alignment. Furthermore, we develop a Frequency-Adaptive Representation Aggregation (FARA) module that leverages wavelet-based frequency decomposition and frequency-specific expert aggregation to enhance anomaly-discriminative visual representations. By jointly strengthening semantic guidance and visual representation learning, VFAD improves both anomaly discrimination and fine-grained localization. Extensive experiments on 13 industrial and medical benchmarks demonstrate that VFAD consistently outperforms existing state-of-the-art ZSAD methods across diverse anomaly scenarios. The code will be publicly available upon publication.
  </details>
