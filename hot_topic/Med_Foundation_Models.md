# 🔍 Med_Foundation_Models Papers · 2026-10-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[TAN: A Size- and Form-Adaptive Masked-Convolution Encoder for Tissue Graphs](https://arxiv.org/abs/2610.23475)**  `arXiv:2610.23475`  `cs.CV`  
  _Jan Herschel, Anselm von Gladiss_
  <details open><summary>Abstract</summary>
  Tissue graphs represent histology images as graphs over tissue-conforming superpixels, which keeps homogeneous tissue regions intact instead of cutting them into rectangular patches. To embed superpixels, current encoders crop them to bounding boxes and then pad, resize, or mask them, so background or fill values can leak into the node features. This matters in practice, and especially in medical imaging, where a prediction should depend on the tissue and not on an arbitrary preprocessing choice: on BACH, changing only the fill of the masked region shifts the accuracy of frozen encoders by up to 6 percentage points, larger than the differences among the four best encoders under mean fill, and the preferred fill differs between datasets, so it cannot be fixed once and for all. We present TAN (Tissue-Aware Network), a compact convolutional encoder (0.41M parameters) that processes each superpixel at its native shape and extent and excludes background from every operation, which makes its embeddings exactly invariant to the fill by construction. Under identical masks and an identical graph classifier, TAN's accuracy on BACH is not significantly different from that of the 303M-parameter foundation model UNI (81.1% vs. 80.7-82.6%, depending on the fill), with ~740x fewer parameters, ~1,190x fewer FLOPs, and no pretraining. On BRACS, TAN is close to a ResNet18 trained under the same protocol and trails the histopathology foundation models. An ablation with TAN's architecture but standard processing of fill-padded crops shows that masking keeps accuracy similar (nominally higher on BACH, lower on BRACS, within noise) at less than half the FLOPs.
  </details>

- **[Input- and Feature-Space Correction for Cross-Hospital IHC Grading](https://arxiv.org/abs/2610.22756)**  `arXiv:2610.22756`  `cs.CV`  
  _Jongwoon Lee, Jhair Gallardo, Christopher Kanan_
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) are trained predominantly on hematoxylin and eosin (H&E) images but are increasingly used as frozen feature extractors for immunohistochemistry (IHC), where cross-hospital differences can impair grading. However, systematic comparisons of correction methods for cross-hospital IHC grading remain limited. To address this gap, we benchmark label-free transformations applied to input images before frozen-FM encoding and to features after frozen-FM encoding using UNI and Virchow2, three IHC markers, and six directed cross-hospital transfers, yielding 12 settings. Among the evaluated input-space methods, our proposed method FIX achieved the largest macro-F1 improvement over no correction, outperforming well-known stain normalization techniques. Among feature-space methods, a simple feature-wise standardization achieved the best improvement over no correction, outperforming CORAL. Under patient-averaged tile-level evaluation, combining FIX with feature-wise standardization improved macro-F1 and quadratic weighted kappa (QWK) by 0.181 and 0.208, respectively, and reduced ordinal error by 0.209 relative to no correction. These results show that input- and feature-space transformations can provide complementary benefits for cross-hospital IHC grading with frozen pathology FMs.
  </details>
