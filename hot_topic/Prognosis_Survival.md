# 🔍 Prognosis_Survival Papers · 2026-03-08

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Ensemble Learning with Sparse Hypercolumns](https://arxiv.org/abs/2603.06036)**  `arXiv:2603.06036`  `cs.CV`  
  _Julia Dietlmeier, Vayangi Ganepola, Oluwabukola G. Adegboro, Mayug Maniparambil, Claudia Mazo, Noel E. O'Connor_
  <details open><summary>Abstract</summary>
  Directly inspired by findings in biological vision, high-dimensional hypercolumns are feature vectors built by concatenating multi-scale activations of convolutional neural networks for a single image pixel location. Together with powerful classifiers, they can be used for image segmentation i.e. pixel classification. However, in practice, there are only very few works dedicated to the use of hypercolumns. One reason is the computational complexity of processing concatenated dense hypercolumns that grows linearly with the size $N$ of the training set. In this work, we address this challenge by applying stratified subsampling to the VGG16 based hypercolumns. Furthermore, we investigate the performance of ensemble learning on sparse hypercolumns. Our experiments on a brain tumor dataset show that stacking and voting ensembles deliver competitive performance, but in the extreme low-shot case of $N \leq 20$, a simple Logistic Regression classifier is the most effective method. For 10% stratified subsampling rate, our best average Dice score is 0.66 for $N=20$. This is a statistically significant improvement of 24.53% over the standard multi-scale UNet baseline ($p$-value = $[3.07e-11]$, Wilcoxon signed-rank test), which is less effective due to overfitting.
  </details>
