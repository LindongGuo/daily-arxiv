# 🔍 Multimodal_ST_Pathology Papers · 2026-05-11

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Qwen-Image-2.0 Technical Report](https://arxiv.org/abs/2605.10730)**  `arXiv:2605.10730`  `cs.CV`  
  _Bing Zhao, Chenfei Wu, Deqing Li, Hao Meng, Jiahao Li, Jie Zhang, et al._
  <details open><summary>Abstract</summary>
  We present Qwen-Image-2.0, an omni-capable image generation foundation model that unifies high-fidelity generation and precise image editing within a single framework. Despite recent progress, existing models still struggle with ultra-long text rendering, multilingual typography, high-resolution photorealism, robust instruction following, and efficient deployment, especially in text-rich and compositionally complex scenarios. Qwen-Image-2.0 addresses these challenges by coupling Qwen3-VL as the condition encoder with a Multimodal Diffusion Transformer for joint condition-target modeling, supported by large-scale data curation and a customized multi-stage training pipeline. This enables strong multimodal understanding while preserving flexible generation and editing capabilities. The model supports instructions of up to 1K tokens for generating text-rich content such as slides, posters, infographics, and comics, while significantly improving multilingual text fidelity and typography. It also enhances photorealistic generation with richer details, more realistic textures, and coherent lighting, and follows complex prompts more reliably across diverse styles. Extensive human evaluations show that Qwen-Image-2.0 substantially outperforms previous Qwen-Image models in both generation and editing, marking a step toward more general, reliable, and practical image generation foundation models.
  </details>

- **[CapCLIP: A Vision-Language Representation Alignment Approach for Wireless Capsule Endoscopy Analysis](https://arxiv.org/abs/2605.08493)**  `arXiv:2605.08493`  `cs.CV`  
  _Haroon Wahab, Irfan Mehmood, Hassan Ugail_
  <details open><summary>Abstract</summary>
  Wireless capsule endoscopy (WCE) enables non-invasive visual assessment of the small bowel, but its clinical utility is constrained by the large volume of frames generated per examination and the difficulty of recognising subtle abnormalities under highly variable imaging conditions. Existing learning-based approaches for WCE are predominantly vision-only, often confined to narrow pathology sets, and show limited transfer across datasets and centres. To address these limitations, this study introduces CapCLIP, a domain-specific vision-language representation learning framework for WCE. CapCLIP aligns capsule endoscopy frames with clinically grounded textual descriptions derived from standardised nomenclature and pathology-aware caption templates, thereby learning embeddings that are both semantically informed and transferable. The proposed framework is evaluated against relevant open-source vision and vision-language foundation models under strict zero-shot conditions using unseen WCE datasets. Evaluation covers three downstream tasks: K-nearest neighbour classification, CLIP-style image-text classification, and text-to-image retrieval. Across these settings, CapCLIP consistently outperforms the compared baselines, with particularly strong gains in zero-shot image-text classification and cross-modal retrieval on out-of-distribution datasets. The results indicate that language-guided representation learning can improve both generalisation and semantic interpretability in WCE analysis. These findings position CapCLIP as a step toward foundation models tailored to capsule endoscopy and support the use of language-grounded WCE analysis.
  </details>
