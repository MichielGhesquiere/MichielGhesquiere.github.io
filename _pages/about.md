---
permalink: /
title: "About"
author_profile: true
show_title: false
redirect_from:
  - /about/
  - /about.html
---

<section class="landing-hero">
  <div class="landing-hero__grid">
    <div>
      <p class="landing-hero__kicker">AI for sensor data and human health</p>
      <h1 class="landing-hero__title">Data Scientist building reliable machine learning systems for health and real-world sensing</h1>
      <p class="landing-hero__lead">
        I work across computer vision, biosignals, and multimodal health data to turn noisy sensing systems into models that are robust, interpretable, and useful in practice. My background combines bioscience engineering, AI, and interdisciplinary research in ophthalmology and biomedical signal processing.
      </p>

      <div class="landing-hero__actions">
        <a class="btn btn--primary" href="{{ base_path }}/projects/">View Projects</a>
        <a class="btn btn--ghost" href="{{ base_path }}/cv/">Read CV</a>
        <a class="btn btn--soft" href="mailto:michiel.ghesquiere@gmail.com">Email</a>
        <a class="btn btn--soft" href="https://github.com/MichielGhesquiere">GitHub</a>
      </div>

      <ul class="landing-hero__meta">
        <li class="metric-chip">Computer Vision</li>
        <li class="metric-chip">Signal Processing</li>
        <li class="metric-chip">Multimodal Health AI</li>
      </ul>
    </div>

    <aside class="landing-hero__panel">
      <h2 class="landing-hero__panel-title">Current direction</h2>
      <p>Building machine learning systems that stay trustworthy when data is messy, multimodal, and clinically relevant.</p>
      <ul class="section-card__chips">
        <li class="metric-chip">Clinical Imaging</li>
        <li class="metric-chip">Wearables</li>
        <li class="metric-chip">Foundation Models</li>
        <li class="metric-chip">Model Reliability</li>
      </ul>
    </aside>
  </div>
</section>

<section class="section-card">
  <div class="section-card__header">
    <p class="section-card__label">Focus Areas</p>
    <h2 class="section-card__title">Building usable machine learning across image, signal, and multimodal data</h2>
  </div>

  <div class="focus-grid">
    <article class="focus-card">
      <h3>Computer Vision</h3>
      <p>Retinal imaging, fundus analysis, segmentation, and domain-robust classification for clinical decision support.</p>
    </article>
    <article class="focus-card">
      <h3>Signal Processing</h3>
      <p>Wearable sensing, biosignal feature extraction, and detection pipelines that remain stable outside ideal lab conditions.</p>
    </article>
    <article class="focus-card">
      <h3>Multimodal Health AI</h3>
      <p>Combining signals, imaging, and context into practical systems for disease detection, monitoring, and personalized feedback.</p>
    </article>
  </div>
</section>

<section class="section-card">
  <div class="section-card__header">
    <p class="section-card__label">Selected Work</p>
    <h2 class="section-card__title">Projects that connect modeling quality to practical outcomes</h2>
  </div>

  <div class="selected-grid">
    <article class="project-card">
      <div class="project-card__header">
        <p class="project-card__label">Retinal Imaging</p>
        <h2>Early Alzheimer&rsquo;s detection via multimodal retinal imaging</h2>
        <p class="project-card__thesis">Novel texture biomarkers and multimodal classification for early-stage disease detection.</p>
      </div>
      <div class="project-card__media project-card__media--contain">
        <img src="{{ base_path }}/images/comprehensive_model_comparison.png" alt="Comparison of retinal imaging model performance">
      </div>
      <ul class="project-card__list">
        <li>Built an end-to-end pipeline from image quality assessment through multimodal classification.</li>
        <li>Identified hyperspectral retinal texture biomarkers linked to early Alzheimer&rsquo;s disease.</li>
        <li>Validated repeatability and reproducibility of imaging biomarkers.</li>
      </ul>
      <div class="project-card__actions">
        <a class="btn btn--primary" href="{{ base_path }}/projects/">Project Details</a>
        <a class="btn btn--soft" href="https://onlinelibrary.wiley.com/doi/abs/10.1111/aos.17369">Abstract</a>
      </div>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <p class="project-card__label">Foundation Models</p>
        <h2>Vision foundation models for glaucoma classification</h2>
        <p class="project-card__thesis">Adapting self-supervised visual representations across devices, sites, and patient populations.</p>
      </div>
      <div class="project-card__media project-card__media--contain">
        <img src="{{ base_path }}/images/umap_embeddings_20250626_190413.png" alt="UMAP projection showing domain shift between glaucoma datasets">
      </div>
      <ul class="project-card__list">
        <li>Explored domain shift across imaging devices and demographics.</li>
        <li>Fine-tuned visual foundation models with multi-source adaptation strategies.</li>
        <li>Focused on robust performance across heterogeneous clinical settings.</li>
      </ul>
      <div class="project-card__actions">
        <a class="btn btn--primary" href="{{ base_path }}/projects/">Project Details</a>
        <a class="btn btn--soft" href="https://github.com/MichielGhesquiere/glaucoma">Code</a>
      </div>
    </article>

    <article class="project-card">
      <div class="project-card__header">
        <p class="project-card__label">Wearables</p>
        <h2>Multimodal seizure detection from wearable sensors</h2>
        <p class="project-card__thesis">Fusing complementary sensor streams to improve detection sensitivity while reducing false alarms.</p>
      </div>
      <div class="project-card__media project-card__media--contain">
        <img src="{{ base_path }}/images/multimodal_seizures.png" alt="Signals from multiple wearable sensors during seizure events">
      </div>
      <ul class="project-card__list">
        <li>Combined EEG, EMG, and accelerometry-derived features in a multimodal detection pipeline.</li>
        <li>Used modality-specific feature extraction and classical ML for reliable event detection.</li>
        <li>Designed the work around clinical usefulness, not just benchmark accuracy.</li>
      </ul>
      <div class="project-card__actions">
        <a class="btn btn--primary" href="{{ base_path }}/projects/">Project Details</a>
        <a class="btn btn--soft" href="{{ base_path }}/cv/">Relevant Experience</a>
      </div>
    </article>
  </div>
</section>

<section class="section-card">
  <div class="section-card__header">
    <p class="section-card__label">Background</p>
    <h2 class="section-card__title">Bridging scientific rigor and practical ML delivery</h2>
  </div>

  <div class="section-card__columns">
    <div>
      <p>I currently work as a Data Scientist at Sentigrate, where I contribute to AI solutions for mental health monitoring using wearable and behavioral data.</p>
    </div>
    <div>
      <p>Before that, I worked at KU Leuven across ophthalmology and biomedical signal processing, building systems for clinical imaging, activity recognition, and biosignal interpretation.</p>
    </div>
  </div>
</section>
