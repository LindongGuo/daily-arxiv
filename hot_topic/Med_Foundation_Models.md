# 🔍 Med_Foundation_Models Papers · 2026-11-17

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[What Matters for Cross-Modal Alignment](https://arxiv.org/abs/2611.20000)**  `arXiv:2611.20000`  `cs.CV` `cs.AI`  
  _Yipeng Sun, Jiajun Wang, Siyuan Mei, Yan Xia, Siming Bayer, Vincent Christlein, et al._
  <details open><summary>Abstract</summary>
  The Platonic Representation Hypothesis posits that models trained on different modalities converge toward a shared representation. Related work aligns frozen image and text encoders on natural images without paired data. We test zero-pair alignment on five datasets across four modalities: natural images, environmental audio, chest radiographs, and 3D computed tomography (CT). It succeeds only on COCO and fails on the other four. We analyze the failures and find that alignment must first locate the subspace where the modalities co-vary and then orient the mapping within it. Consistent with previous studies, medical imaging is the hardest case: its shared subspace carries the smallest fraction of the variance. When this fraction is small, alignment needs image-text pairs, and random-matrix theory predicts how many pairs are needed. These findings motivate LightAlign: a few pairs let a ridge regression between two frozen encoders locate and orient the mapping simultaneously, and a classifier fitted only on report text then predicts findings from the mapped images. On 3D CT, LightAlign surpasses models trained end to end on image-report pairs without finding-level labels: with only 200 pairs, LightAlign outperforms CT-CLIP on CT-RATE (0.754 vs. 0.733 AUROC), and with only 100 CT-RATE pairs, it does so on RAD-ChestCT, an out-of-distribution dataset from a different hospital. On CheXpert, it reaches 0.862 mean AUROC with only about 5% as many pairs as models trained on MIMIC-CXR.
  </details>

- **[A Subspecialty Diagnostic System Powered by Self-Supervised Learning for Cervical Histopathology](https://arxiv.org/abs/2510.10196)**  `arXiv:2510.10196`  `cs.CV`  
  _Yizhi Wang, Li Chen, Qiang Huang, Tian Guan, Xi Deng, Zhiyuan Shen, et al._
  <details open><summary>Abstract</summary>
  Cervical cancer remains a major malignancy in women, with large-scale human papillomavirus-based screening generating a large volume of biopsies and, for advanced cases, surgical specimens, imposing an overwhelming diagnostic burden that necessitates precise histopathological evaluation. Although deep learning shows promise, general foundation models offer a broader reach but remain limited in capturing subspecialty-specific features and task adaptability. We introduce the Cervical Subspecialty Pathology (CerS-Path) diagnostic system, built upon the subspecialized dataset and developed through two synergistic pretraining stages: self-supervised learning on approximately 190 million tissue patches to build a cervical-specific feature extractor, and multimodal enhancement with 2.5 million image-text pairs, followed by diagnostic functions integration and downstream task enhancement. CerS-Path integrates eight functions -- across morphological diagnosis, predictive analytics, and multimodal tasks -- to cover the diagnostic workflow from biopsies to resection specimens. Comprehensive evaluations demonstrate improved performance in cervical pathology in female patients, where CerS-Path outperforms state-of-the-art foundation models across 26 of 30 diagnostic tasks. Furthermore, in multicenter retrospective and prospective validation across six independent cohorts of women, CerS-Path achieves up to 99% sensitivity for clinically relevant lesion detection with acceptable specificity across sites, highlighting its potential for screening-derived histopathology and suitability for integration into high-volume diagnostic pathways.
  </details>
