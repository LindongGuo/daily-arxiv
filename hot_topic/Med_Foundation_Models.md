# 🔍 Med_Foundation_Models Papers · 2026-08-12

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Look What the Probes Dragged In! Real-World Chest X-ray Shortcuts in MedCLIP](https://arxiv.org/abs/2608.12086)**  `arXiv:2608.12086`  `cs.CV` `cs.LG`  
  _Nikolette Pedersen, Regitze Sydendal, Veronika Cheplygina, Théo Sourget_
  <details open><summary>Abstract</summary>
  Vision-language models, such as contrastive language-image pre-training (CLIP)-based approaches, have reached state-of-the-art (SOTA) results in medical artificial intelligence. However, recent work reveals that CLIP-based models remain vulnerable to shortcuts. We investigate how real-world shortcuts manifest across different layers of the medical CLIP-based model, MedCLIP, and its vision encoder, a frozen ResNet-50. We attach 17 linear classification probes to the intermediate layers of the ResNet-50 and train them on three different dataset configurations and targets: NIH-CXR14 (pneumothorax) and PadChest (cardiomegaly and pneumothorax). This setup allows us to observe model behaviour during evaluation using subgroup-based calibration and layer-wise confidence curves. We find that the final linear probes achieve a high AUROC but poor calibration in the models. The layer-wise confidence analyses suggest that shortcuts emerge at different depths. Patterns consistent with localised shortcuts, such as drains, appear at later layers, while patterns consistent with diffuse shortcuts, such as scanner-specific noise patterns, emerge earlier, aligning with previous work. Finally, we conduct a manual analysis of the images, which reveals data quality issues in both NIH-CXR14 and PadChest. Our findings underscore that even SOTA models remain vulnerable to shortcuts, and the need for high-quality and well-annotated datasets to draw solid conclusions. Code can be found on our GitHub:this https URL.
  </details>

- **[Dual Anchors, Do It Better: Hierarchical Group Merging for Zero-Shot Anomaly Detection](https://arxiv.org/abs/2608.11933)**  `arXiv:2608.11933`  `cs.CV`  
  _Jimin Roh, DongKyu Kim, Suk-Ju Kang_
  <details open><summary>Abstract</summary>
  Zero-shot anomaly detection (ZSAD) aims to identify anomalies in unseen domains, a setting that is particularly critical for industrial and medical applications where domain shifts are prevalent. However, most CLIP-based ZSAD methods anchor semantics solely on the text modality, making performance highly sensitive to prompt design and leading to weak visual grounding. To mitigate these limitations, we propose a Dual-Anchor framework that complements conventional text anchors with hierarchical image anchors constructed via a top-down grouping mechanism. This mechanism progressively aggregates local-to-global image features to form normal and abnormal group tokens, which serve as image anchors and act as gating signals in a Group-Gated Token Refiner to enhance the global representation. The refined image anchors are then fused with text prompts to construct dynamic state prompts. By jointly reinforcing visual and textual semantics, our framework stabilizes image-text alignment, reduces prompt dependency, and achieves strong generalization across 8 industrial and 6 medical benchmarks.
  </details>
