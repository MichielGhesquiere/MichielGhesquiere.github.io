---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
eyebrow: "Applied Work"
intro: "Selected projects across clinical imaging, biosignals, multimodal sensing, and real-world computer vision."
---

<div class="project-grid">
  <article class="project-card">
    <div class="project-card__header">
      <p class="project-card__label">Clinical Imaging</p>
      <h2>Early Alzheimer&rsquo;s detection via multimodal retinal imaging</h2>
      <p class="project-card__thesis">Novel texture biomarkers in hyperspectral retinal imaging paired with multimodal classification for early disease detection.</p>
    </div>
    <div class="project-card__media project-card__media--contain">
      <img src="{{ base_path }}/images/comprehensive_model_comparison.png" alt="Performance comparison of retinal imaging models for Alzheimer detection">
    </div>
    <ul class="project-card__list">
      <li>Developed the full workflow from image quality assessment through preprocessing, feature extraction, and classification.</li>
      <li>Created a novel hyperspectral texture biomarker aimed at early-stage disease sensitivity.</li>
      <li>Assessed repeatability and reproducibility to keep the biomarkers clinically credible.</li>
    </ul>
    <div class="project-card__actions">
      <a class="btn btn--soft" href="https://onlinelibrary.wiley.com/doi/abs/10.1111/aos.17369">Abstract</a>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__header">
      <p class="project-card__label">Foundation Models</p>
      <h2>Vision foundation models for glaucoma classification</h2>
      <p class="project-card__thesis">Addressing domain shift across imaging devices and demographics with self-supervised visual representations.</p>
    </div>
    <div class="project-card__media project-card__media--contain">
      <img src="{{ base_path }}/images/umap_embeddings_20250626_190413.png" alt="UMAP embeddings showing domain shift between glaucoma datasets">
    </div>
    <ul class="project-card__list">
      <li>Leveraged visual foundation models pre-trained with self-supervised learning.</li>
      <li>Implemented multi-source fine-tuning and domain adaptation techniques.</li>
      <li>Focused on robustness across different devices, demographics, and clinical settings.</li>
    </ul>
    <div class="project-card__actions">
      <a class="btn btn--primary" href="https://github.com/MichielGhesquiere/glaucoma">View Code</a>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__header">
      <p class="project-card__label">Computer Vision + Behavior</p>
      <h2>Camera-based activity recognition for animal welfare</h2>
      <p class="project-card__thesis">Hybrid detection pipeline combining object detection with motion analysis for early welfare risk recognition.</p>
    </div>
    <div class="project-card__media project-card__media--contain">
      <img src="{{ base_path }}/images/overview-algorithm-movement-detection.png" alt="Overview of the hybrid movement detection algorithm">
    </div>
    <ul class="project-card__list">
      <li>Combined YOLO-based object detection with Gaussian Mixture Model motion analysis.</li>
      <li>Built a real-time monitoring system for welfare-compromising behavior.</li>
      <li>Designed for deployment realism rather than only static offline evaluation.</li>
    </ul>
    <div class="project-card__media">
      <video controls preload="metadata" playsinline>
        <source src="{{ base_path }}/images/YOLO_chicken_head_clipped.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div class="project-card__actions">
      <a class="btn btn--soft" href="https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9993097125501488&amp;context=L&amp;vid=32KUL_KUL:KULeuven&amp;lang=en&amp;search_scope=All_Content&amp;adaptor=Local%20Search%20Engine&amp;tab=all_content_tab&amp;query=any,contains,michiel%20ghesquiere">Thesis</a>
      <a class="btn btn--soft" href="https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9994277629301488&amp;context=L&amp;vid=32KUL_KUL:KULeuven&amp;lang=en&amp;search_scope=All_Content&amp;adaptor=Local%20Search%20Engine&amp;tab=all_content_tab&amp;query=any,contains,michiel%20ghesquiere">Publication</a>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__header">
      <p class="project-card__label">Wearable Health AI</p>
      <h2>Multimodal seizure detection</h2>
      <p class="project-card__thesis">Combining wearable sensor modalities to improve seizure detection sensitivity while reducing false alarms.</p>
    </div>
    <div class="project-card__media project-card__media--contain">
      <img src="{{ base_path }}/images/schematic-SD-wearables.png" alt="Schematic overview of the wearable seizure detection setup">
    </div>
    <ul class="project-card__list">
      <li>Designed modality-specific feature extraction for EEG, EMG, and accelerometry.</li>
      <li>Used multimodal fusion to improve reliability beyond single-sensor baselines.</li>
      <li>Balanced detection performance against the practical cost of false alarms.</li>
    </ul>
    <div class="project-card__media project-card__media--contain">
      <img src="{{ base_path }}/images/multimodal_seizures.png" alt="Sensor traces around seizure events">
    </div>
    <div class="project-card__actions">
      <a class="btn btn--soft" href="{{ base_path }}/cv/">See CV Details</a>
    </div>
  </article>
</div>
