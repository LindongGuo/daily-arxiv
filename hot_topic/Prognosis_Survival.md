# 🔍 Prognosis_Survival Papers · 2026-07-14

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[SpikeDS: Dual Sparsity Spikformer for Perineural Invasion Prediction in 3D MRI](https://arxiv.org/abs/2607.11986)**  `arXiv:2607.11986`  `cs.CV` `cs.LG`  
  _Induk Um, Youngung Han, Kyeonghun Kim, Yului Jeong, Jina Jeong, Hyunsu Go, et al._
  <details open><summary>Abstract</summary>
  Perineural invasion (PNI) is associated with poor prognosis in cholangiocarcinoma (CCA). However, its detection from 3D MRI remains challenging due to the subtle and spatially heterogeneous imaging signatures at the tumor periphery. Capturing such spatially sparse cues necessitates volumetric analysis of 3D MRI, but existing deep learning approaches incur prohibitive computational costs on volumetric medical images, limiting their clinical deployment. We propose Dual Sparsity Spikformer (SpikeDS), a spiking neural network architecture that jointly exploits activation sparsity from binary spike communication and spatial sparsity from window pruning based on firing rates. SpikeDS introduces Dual Sparsity Spiking Attention (DSSA), which combines two complementary mechanisms. The first is Window-based Expert Mixture Spiking Attention (W-EMSA), which selectively applies attention only to salient windows identified by their firing rates. The second is Cross-Window Spiking Self-Attention (CW-SSA), which enables global context exchange through an asymmetric scheme in which pruned windows still contribute as key-value sources. Evaluated on a clinical cohort of 139 CCA patients via 5-fold cross-validation, SpikeDS achieves an AUC of 0.753 while consuming only 14.4 mJ, surpassing the best baseline in both AUC and energy efficiency. These results suggest that dual sparsity provides an effective hardware-aware strategy for improving the efficiency of 3D spiking transformers without compromising diagnostic performance.
  </details>

- **[CRC-HGD: A Histopathological Image Dataset for Grading Colorectal Cancer](https://arxiv.org/abs/2607.12750)**  `arXiv:2607.12750`  `cs.CV`  
  _Elham Amjadi, Amin Bahreini, Sayed Mohammad Hasan Emami, Sayyed Mohammadreza Hakimian, Alireza Fahim, Hojjatollah Rahimi, et al._
  <details open><summary>Abstract</summary>
  Colorectal cancer (CRC) is the third most common cancer worldwide and the second leading cause of cancer-related deaths globally, with approximately 1,926,425 new cases and 904,019 deaths reported in 2022. Accurate histologic grading plays a critical role in prognosis and treatment planning for colorectal adenocarcinoma. In recent years, artificial intelligence and its subcategories, including machine learning and deep learning, have been increasingly employed for automated cancer detection and classification. An appropriate and well-organized dataset is the essential first step to achieve this goal. This paper introduces CRC-HGD, a histopathological microscopy image dataset of 1,914 images obtained from 214 colorectal adenocarcinoma patients (Grade I: 106, Grade II: 75, Grade III: 33). The specimens are H&E-stained colorectal tissue sections acquired at the Poursina Hakim Research Center of Isfahan University of Medical Sciences, Iran, diagnosed between 2014 and 2019, and graded according to the World Health Organization (WHO) criteria into three grades: well-differentiated (Grade I), moderately differentiated (Grade II), and poorly differentiated (Grade III). For each specimen, four magnification levels are provided: 4x, 10x, 20x, and 40x. The dataset is accessible via Mendeley Data (this https URL) and atthis http URL, where the latest version is also available. The distinctive feature of this dataset is the provision of labeled specimens across all three differentiation grades at multiple magnification levels, enabling comprehensive computational analysis of colorectal cancer grading.
  </details>

- **[Together, Then Apart: Balancing Alignment and Distinctiveness for Multimodal Survival Analysis](https://arxiv.org/abs/2511.18089)**  `arXiv:2511.18089`  `cs.CV`  
  _Wenjing Liu, Qin Ren, Wen Zhang, Yuewei Lin, Chenyu You_
  <details open><summary>Abstract</summary>
  Multimodal survival analysis aims to improve cancer prognosis using heterogeneous biomedical data, such as histopathology images and genomic profiles. A common strategy is to align representations across modalities so that shared signals can be captured. However, strong cross-modal alignment can also remove modality-specific evidence that is critical for survival prediction. In this paper, we revisit multimodal survival learning from a simple observation: effective models should first discover shared patterns across modalities, and then preserve modality-specific signals. This motivates a representation learning principle that we refer to as Together Then Apart. Based on this idea, we propose TTA, a framework that balances cross-modal alignment and representation distinctiveness. TTA first performs prototype-based alignment to capture shared survival-related structures between modalities. It then encourages modality-specific distinctiveness through an anchor-guided contrastive objective. To further account for modality imbalance and noisy correspondences, we model cross-modal interactions using unbalanced optimal transport. We evaluate the proposed approach on multiple TCGA cancer cohorts with paired histopathology and genomic data. TTA consistently improves survival prediction over recent multimodal survival models. Moreover, the learned prototype structures reveal interpretable cross-modal patterns associated with clinical outcomes.
  </details>
