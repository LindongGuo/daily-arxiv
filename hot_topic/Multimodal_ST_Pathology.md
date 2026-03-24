# 🔍 Multimodal_ST_Pathology Papers · 2026-03-23

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Detecting Neurovascular Instability from Multimodal Physiological Signals Using Wearable-Compatible Edge AI: A Responsible Computational Framework](https://arxiv.org/abs/2603.20442)**  `arXiv:2603.20442`  `cs.LG` `cs.AI`  
  _Truong Quynh Hoa, Hoang Dinh Cuong, Truong Xuan Khanh_
  <details open><summary>Abstract</summary>
  We propose Melaguard, a multimodal ML framework (Transformer-lite, 1.2M parameters, 4-head self-attention) for detecting neurovascular instability (NVI) from wearable-compatible physiological signals prior to structural stroke pathology. The model fuses heart rate variability (HRV), peripheral perfusion index, SpO2, and bilateral phase coherence into a composite NVI Score, designed for edge inference (WCET <=4 ms on Cortex-M4). NVI - the pre-structural dysregulation of cerebrovascular autoregulation preceding overt stroke - remains undetectable by existing single-modality wearables. With 12.2 million incident strokes annually, continuous multimodal physiological monitoring offers a practical path to community-scale screening. Three-stage independent validation: (1) synthetic benchmark (n=10,000), AUC=0.88 [0.83-0.92]; (2) clinical cohort PhysioNet CVES (n=172; 84 stroke, 88 control) - Transformer-lite achieves AUC=0.755 [0.630-0.778], outperforming LSTM (0.643), Random Forest (0.665), SVM (0.472); HRV-SDNN discriminates stroke (p=0.011); (3) PPG pipeline PhysioNet BIDMC (n=53) -- pulse rate r=0.748 and HRV surrogate r=0.690 vs. ECG ground truth. Cross-modality validation on PPG-BP (n=219) confirms PPG morphology classifies cerebrovascular disease at AUC=0.923 [0.869-0.968]. Multimodal fusion consistently outperforms single-modality baselines. Code:this https URL
  </details>

- **[Spatial Transcriptomics as Images for Large-Scale Pretraining](https://arxiv.org/abs/2603.13432)**  `arXiv:2603.13432`  `cs.CV` `cs.AI`  
  _Yishun Zhu, Jiaxin Qi, Jian Wang, Yuhua Zheng, Jianqiang Huang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) profiles thousands of gene expression values at discrete spots with precise coordinates on tissue sections, preserving spatial context essential for clinical and pathological studies. With rising sequencing throughput and advancing platforms, the expanding data volumes motivate large-scale ST pretraining. However, the fundamental unit for pretraining, i.e., what constitutes a single training sample, remains ill-posed. Existing choices fall into two camps: (1) treating each spot as an independent sample, which discards spatial dependencies and collapses ST into single-cell transcriptomics; and (2) treating an entire slide as a single sample, which produces prohibitively large inputs and drastically fewer training examples, undermining effective pretraining. To address this gap, we propose treating spatial transcriptomics as croppable images. Specifically, we define a multi-channel image representation with fixed spatial size by cropping patches from raw slides, thereby preserving spatial context while substantially increasing the number of training samples. Along the channel dimension, we define gene subset selection rules to control input dimensionality and improve pretraining stability. Extensive experiments show that the proposed image-like dataset construction for ST pretraining consistently improves downstream performance, outperforming conventional pretraining schemes. Ablation studies verify that both spatial patching and channel design are necessary, establishing a unified, practical paradigm for organizing ST data and enabling large-scale pretraining.
  </details>
