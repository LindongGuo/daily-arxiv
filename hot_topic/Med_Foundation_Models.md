# 🔍 Med_Foundation_Models Papers · 2026-11-03

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[From Natural Images to Medical Scans: Transferability of Diffusion Models for Medical Image Generation](https://arxiv.org/abs/2611.05192)**  `arXiv:2611.05192`  `cs.CV`  
  _Efthymios Georgiou, Ioannis Kakogeorgiou, Sarah Brüningk_
  <details open><summary>Abstract</summary>
  Transfer learning from natural images is standard in supervised and increasingly adopted in self-supervised medical image analysis, but its role in generative modelling, and in particular diffusion denoisers, remains underexplored. Medical diffusion models typically train the denoiser from scratch, with no systematic evaluation of natural-image transfer. We analyse this across latent and pixel paradigms, model sizes (131M-952M) and two radiology datasets (RadImageNet, BraTS), and ask which aspects of transfer support generation. We find that: i) Natural-image initialisation consistently improves generation, by 21-34% relative gFID in pixel space against 14% in latent space, where the tokeniser supplies much of the prior. gFID gains mirror downstream pathology classification and radiomic-feature FD, both proxies for clinical fidelity. ii) Benefits reflect spatial structure, not semantics: semantic probing does not predict generation quality, whereas a spatial-structure metric adapted to internal denoiser representations tracks gFID at $|r|=0.85$, positioning spatial organisation as a channel through which pretraining manifests. iii) Mixed-domain denoiser training shows that natural and medical images share similar layer-wise representations up to the late blocks, and mixing natural images into medical training improves fidelity. iv) Transfer benefit is tied to natural image initialisation, outperforming in-domain medical pretraining and several reinitialisation schemes. Overall, natural image denoisers transfer positively to medical ones in our setup. Code is available atthis https URL
  </details>
