---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Featured Projects

### 🧠 Early Alzheimer's Detection via Multimodal Retinal Imaging
**Key Innovation:** Novel texture biomarkers in hyperspectral retinal imaging, multimodal classifiaction achieving AUC 0.84

- Developed end-to-end pipeline from image quality assessment to multimodal classification
- Created novel hyperspecrtal imaging texture biomarker for early disease detection
- Assessed repeatability and reproducibility of imaging biomarkers

[Abstract](https://onlinelibrary.wiley.com/doi/abs/10.1111/aos.17369) *(Preliminary results - full paper coming soon!)*

---

### 👁️ Vision Foundation Models for Glaucoma Classification
**Key Innovation:** Addressing domain shift across imaging devices and demographics

<div style="text-align: center;">
  <img src="/images/umap_embeddings_20250626_190413.png" alt="UMAP embeddings showing domain shift between datasets" style="max-width: 100%; height: auto; margin: 20px 0;">
  <p><em>UMAP embeddings of image features by dataset and classification label (Normal vs Glaucoma), showing domain shift between different imaging devices/clinical settings/demographics</em></p>
</div>

- Leveraged Vision Foundation Models (VFM) pre-trained with self-supervised learning
- Implemented multi-source domain fine-tuning techniques
- Applied domain adaptation to handle demographic and device variations
- Achieved robust performance across different clinical settings

[View Code](https://github.com/MichielGhesquiere/glaucoma)

### 🐔 Camera-based Activity Recognition for Animal Welfare
**Key Innovation:** Hybrid approach combining object detection with motion analysis

<div style="text-align: center;">
  <img src="/images/overview-algorithm-movement-detection.png" alt="Overview of the hybrid algorithm for movement detection" style="max-width: 100%; height: auto; margin: 20px 0;">
  <p><em>Overview of the developed hybrid algorithm combining YOLOv5 object detection with motion analysis</em></p>
</div>

<div style="text-align: center;">
  <video width="100%" max-width="800px" height="auto" controls style="margin: 20px 0;">
    <source src="/images/YOLO_chicken_head_clipped.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Real-time head detection of laying hens using fine-tuned YOLOv5 on custom labeled dataset</em></p>
</div>

- Developed real-time animal behavior monitoring system
- Combined YOLOv5 object detection with Gaussian Mixture Model motion detection
- Achieved early detection of welfare-compromising behaviors

**Resources:**
- [Thesis](https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9993097125501488&context=L&vid=32KUL_KUL:KULeuven&lang=en&search_scope=All_Content&adaptor=Local%20Search%
Engine&tab=all_content_tab&query=any,contains,michiel%20ghesquiere)
- [Publication](https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9994277629301488&context=L&vid=32KUL_KUL:KULeuven&lang=en&search_scope=All_Content&adaptor=Local%20Search%20Engine&tab=all_content_tab&query=any,contains,michiel%20ghesquiere)

---

### 🧠 Multimodal Seizure Detection
**Key Innovation:** Fusion of multiple wearable sensor modalities for improved detection

<div style="text-align: center;">
  <img src="/images/schematic-SD-wearables.png" alt="Schematic setup of wearable sensors for seizure detection" style="max-width: 100%; height: auto; margin: 20px 0;">
  <p><em></em></p>
</div>

- Modality specific feature extraction + SVM classification
- By combining multiple modalities, we could improve sensitivity and reduce false alarm rate

<div style="text-align: center;">
  <img src="/images/multimodal_seizures.png" alt="Multimodal signals during seizure events" style="max-width: 100%; height: auto; margin: 20px 0;">
  <p><em></em></p>
</div>

[Thesis](https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9993576486601488&context=L&vid=32KUL_KUL:KULeuven&lang=en&search_scope=All_Content&adaptor=Local%20Search%20Engine&tab=all_content_tab&query=any,contains,michiel%20ghesquiere)
