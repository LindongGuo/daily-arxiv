# 🔍 Prognosis_Survival Papers · 2026-07-28

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[HeAD-CP: Heterophily-Aware Diffused Conformal Prediction Sets for Graph Neural Networks](https://arxiv.org/abs/2607.25273)**  `arXiv:2607.25273`  `cs.LG`  
  _Phan Binh Nguyen Lam, Nguyen Thai Anh_
  <details open><summary>Abstract</summary>
  Conformal prediction (CP) provides distribution-free uncertainty quantification, and its extension to graphs is an active research direction. Diffused Adaptive Prediction Sets (DAPS) is a widely used graph-aware diffusion baseline, propagating Adaptive Prediction Sets (APS) non-conformity scores along edges with a uniform coefficient $\lambda$. We identify a fundamental shortcoming of this design: the uniform low-pass diffusion presupposes graph homophily and proves detrimental on heterophilic graphs, enlarging the mean prediction-set size by up to 10.6% relative to plain APS. To mitigate this, we propose HeAD-CP, a family of node-wise diffusion variants whose coefficients are determined by a label-free local-homophily estimate derived from the GNN softmax. Three variants, namely signed-$\gamma$, edge-compatibility, and a DAPS-baseline-with-correction, are most effective at extreme heterophily, intermediate heterophily, and moderate-to-high homophily, respectively, and all preserve the marginal coverage guarantee. On ten benchmarks, the HeAD-CP family stays at or below plain APS on every dataset, while DAPS exceeds APS on six. The post-hoc oracle over the family improves over DAPS on 8/10 datasets at $p<0.01$ (paired Wilcoxon), with the largest gains on heterophilic graphs (10.3% on Texas); on the two homophilic datasets where DAPS still wins (CiteSeer, PubMed), it retains a marginal advantage of at most 0.002, statistically insignificant on CiteSeer ($p=0.23$). Designing a calibrated label-free selector that approaches this oracle is the main outstanding empirical question.
  </details>

- **[Explainable Flood Segmentation on Sentinel-1 SAR1 Imagery Using CNN and Transformer Architectures](https://arxiv.org/abs/2606.16302)**  `arXiv:2606.16302`  `cs.CV`  
  _Arundhuti Banerjee, David Daou_
  <details open><summary>Abstract</summary>
  Rapid and accurate flood prediction is essential for disaster response and mitigation planning. Synthetic Aperture Radar (SAR) sensors in satellites are well-suited for this purpose because they operate independently of weather and daylight conditions. Although SAR-based data enable all-weather flood monitoring, distinguishing flooded land from permanent water remains a significant challenge, particularly when flooding is defined strictly as inundated land. This study provides a comprehensive comparison of convolutional neural network (CNN) and vision transformer architectures for multi-class flood segmentation using Sentinel-1 SAR imagery, specifically trained to separate flooded land from permanent water bodies and land. Three state-of-the-art (SOTA)CNN-based models, U-Net, U-Net++, and DeepLabV3 with ResNet-34 backbone, and three SegFormer variants (b0,b1,b2) were evaluated in two benchmark datasets, the ETCI NASA dataset and SenFloods11, using scene-based data splits to ensure a realistic assessment of spatial generalization. The results demonstrate that SegFormer-b2 significantly outperforms the U-Net baseline on the ETCI dataset (higher flood IoU across all 7 test scenes in the Wilcoxon signed-rank test), while after fine-tuning on Sen1Floods11, the advantage narrows to within the range of scene variability and is concentrated in spatially fragmented flood events. The study includes both qualitative and quantitative explainability techniques to visually comprehend model decisions and systematically assess prediction reliability. Qualitative analysis reveals that SegFormer-b2 produces more spatially coherent Grad-CAM activations focused on flood-relevant features, while U-Net generates more informative uncertainty estimates along flood boundaries.
  </details>
