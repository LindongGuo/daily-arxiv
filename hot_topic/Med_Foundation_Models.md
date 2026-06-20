# 🔍 Med_Foundation_Models Papers · 2026-06-19

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[PU-UNet: Stable Multiplicative Interactions for Medical Image Segmentation](https://arxiv.org/abs/2606.20035)**  `arXiv:2606.20035`  `cs.CV` `cs.LG`  
  _Ziyuan Li, Osamah Sufyan, Uwe Jaekel, Babette Dellen_
  <details open><summary>Abstract</summary>
  Many dense prediction networks rely on additive feature transformations and model higher-order feature interactions only implicitly. Product units provide an explicit mechanism for multiplicative feature modeling, but their logarithmic--exponential formulation can cause numerical instability, which has limited their use in deep dense prediction networks. In this work, we propose Product-Unit U-Net (PU-UNet), a residual U-Net that integrates stable product-unit residual blocks into rich low-resolution stages for medical image segmentation. The proposed formulation combines smooth positivity mapping with log-domain clipping, enabling stable multiplicative feature learning with negligible computational overhead. On ISIC 2018, Kvasir-SEG, and BUSI, PU-UNet achieves Dice scores of 0.942, 0.959, and up to 0.925, respectively. Compared with a matched Residual U-Net baseline, PU-UNet consistently improves Dice and IoU while keeping parameters, FLOPs, and inference latency nearly unchanged, and reduces the image-level false-positive rate on normal BUSI cases from 0.077 to zero. Ablation studies suggest that the gains are associated with product-unit interactions, are strongest under low-resolution placement, and benefit from the proposed stabilization design. These results suggest that stable product-unit residual learning can be an effective way to enhance U-Net-style segmentation networks with explicit multiplicative interactions.
  </details>
