# 🔍 Med_Foundation_Models Papers · 2026-10-21

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[From Theory to Decision Rule: Calibrating the Noisy-Label Crossover for Vision-Language Model Weak Supervision Across Three Medical-Imaging Benchmarks](https://arxiv.org/abs/2605.24771)**  `arXiv:2605.24771`  `cs.CV` `cs.AI` `cs.LG`  
  _Bruce Changlong Xu, Jose K. James, Alexander J. Ryu_
  <details open><summary>Abstract</summary>
  In medical imaging, small sets of expert labels are often combined with zero-shot pseudo-labels from a vision-language model (VLM). When the expert-labeled set is very small, the extra pseudo-labels reduce variance and improve accuracy. Once a classifier trained on expert labels alone reaches the accuracy of the weak labeler, however, adding pseudo-labels lowers test performance. We measure where this crossover occurs on PatchCamelyon histopathology, ISIC 2019 dermoscopy, and NIH ChestX-ray14 radiography using pseudo-labels from BiomedCLIP and PubMedCLIP across six student architectures ($8\mathrm{M}$ to $89\mathrm{M}$ parameters). Weak labels stop helping after $20$--$50$ expert labels on ISIC 2019, about $100$ on PatchCamelyon, and $250$--$500$ on NIH ChestX-ray14. Above those budgets, adding $10{,}000$ pseudo-labels reduces test macro-AUC by up to $0.14$ points with BiomedCLIP ($0.23$ with PubMedCLIP) on ISIC 2019, $0.10$ on PatchCamelyon, and $0.08$ on NIH ChestX-ray14. Across the six student architectures, the weak-label ceiling stays within a $0.024$ AUC range ($0.841$--$0.865$), indicating that the VLM labeler, rather than student size, limits performance. Comparing VLM pseudo-labels with random label flips at the same error rate shows that systematic VLM mistakes yield $0.09$--$0.20$ lower AUC than random noise on PatchCamelyon and ISIC 2019, but $0.03$--$0.04$ higher AUC on 15-class NIH ChestX-ray14, where per-finding crossovers also span more than a $20\times$ range. A simple bias-variance rule estimated from the weak labeler's validation accuracy and small expert-only runs predicts whether pseudo-labels will help or hurt in all $30$ statistically significant settings ($39/42$ overall).
  </details>

- **[One-Slide Calibration of Pathology Foundation Models](https://arxiv.org/abs/2610.08944)**  `arXiv:2610.08944`  `cs.CV` `cs.AI`  
  _Ming Ren Hou, Tianyi Huang_
  <details open><summary>Abstract</summary>
  Scanner variation changes how pathology foundation models represent the same tissue. We introduce SlideRuler, which uses other regions within a slide as internal controls to predict a query region's scanner-induced shift. A transfer map learned from paired rescans enables calibration from a single scan at inference while keeping the foundation model fixed. Across two encoders and five SCORPION scanners, learned transfer reduces mean target-to-source embedding distance by 16.3-38.5% relative to raw embeddings. Replacing controls with unrelated same-scanner regions reveals a positive same-slide contribution in all four evaluation settings, including scanner holdout. A source-anchored variant reduces source-feature displacement by 47.7-83.6% relative to learned transfer while retaining most of its alignment gain. By drawing calibration information from the slide itself, SlideRuler offers a path toward more consistent use of frozen pathology models across imaging systems.
  </details>
