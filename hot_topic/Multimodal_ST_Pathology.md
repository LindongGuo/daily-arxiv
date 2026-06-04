# 🔍 Multimodal_ST_Pathology Papers · 2026-06-03

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Radiomic Feature Selection Using Gradient Loss of Deep Neural Network for Lung Cancer Stage Detection](https://arxiv.org/abs/2606.04453)**  `arXiv:2606.04453`  `cs.CV` `cs.LG`  
  _Hina Shakir, Mohammad Mohatram, Javeed Hussain, Syed Rizwan Ali, Muhammad Irfan Memon_
  <details open><summary>Abstract</summary>
  Radiomics enables extraction of quantitative imaging biomarkers from medical images and has become an important tool for computer-aided cancer diagnosis. However, radiomics datasets are typically high-dimensional with limited samples, making feature selection a critical step for building reliable predictive models. This study proposes a Gradient-Loss Recursive Feature Elimination (GL-RFE) framework that integrates gradient sensitivity analysis from a deep neural network to identify the most influential radiomic features for lung cancer stage detection. A total of 106 radiomic features were extracted from chest Computed Tomography (CT) scans using the PyRadiomics extension of the 3D Slicer platform. The proposed method evaluates feature importance by computing gradients of the network loss with respect to input features and recursively eliminates features with minimal contribution. The resulting top-15 radiomic features are used to train a deep neural network classifier for distinguishing early-stage and advanced-stage lung cancer. The proposed framework achieves strong classification performance, with accuracy of 90.22%, precision of 90.10%, recall of 90.24%, and F1-score of 90.16% on the test dataset. Visualization analyses, including correlation heat maps and distribution plots, further confirm reduced feature redundancy and improved class separability. Compared to conventional feature selection techniques, GL-RFE effectively captures nonlinear feature interactions and enhances model generalization. The presented protocol provides a reproducible and interpretable methodology for radiomics-based cancer stage detection and is particularly suitable for high-dimensional, small-sample biomedical datasets, with potential applications in other domains such as genomics and multimodal clinical analysis.
  </details>

- **[Spatial Transcriptomics as Images for Large-Scale Pretraining](https://arxiv.org/abs/2603.13432)**  `arXiv:2603.13432`  `cs.CV` `cs.AI`  
  _Yishun Zhu, Jiaxin Qi, Jian Wang, Yuhua Zheng, Jianqiang Huang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) profiles thousands of gene expression values at discrete spots with precise coordinates on tissue sections, preserving spatial context essential for clinical and pathological studies. With rising sequencing throughput and advancing platforms, the expanding data volumes motivate large-scale ST pretraining. However, the fundamental unit for pretraining, i.e., what constitutes a single training sample, remains ill-posed. Existing choices fall into two camps: (1) treating each spot as an independent sample, which discards spatial dependencies and collapses ST into single-cell transcriptomics; and (2) treating an entire slide as a single sample, which produces prohibitively large inputs and drastically fewer training examples, undermining effective pretraining. To address this gap, we propose treating spatial transcriptomics as croppable images. Specifically, we define a multi-channel image representation with fixed spatial size by cropping patches from raw slides, thereby preserving spatial context while substantially increasing the number of training samples. Along the channel dimension, we define gene subset selection rules to control input dimensionality and improve pretraining stability. Extensive experiments show that the proposed image-like dataset construction for ST pretraining consistently improves downstream performance, outperforming conventional pretraining schemes. Ablation studies verify that both spatial patching and channel design are necessary, establishing a unified, practical paradigm for organizing ST data and enabling large-scale pretraining.
  </details>
