---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
  .pj-intro { color: #494e52; margin-bottom: 2em; }
  .pj-section { margin: 2.5em 0 0.4em; }
  .pj-section-sub { color: #7a8288; font-size: 0.85em; margin: 0 0 1.2em; }
  .pj-meta { font-size: 0.72em; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: #7a8288; margin: 0 0 0.35em; }
  .pj-title { font-size: 1.12em; line-height: 1.3; margin: 0 0 0.45em; padding: 0; border: 0; }
  .pj-text { font-size: 0.9em; line-height: 1.6; margin: 0 0 0.7em; }
  .pj-tags { display: flex; flex-wrap: wrap; gap: 6px; margin: 0 0 0.8em; padding: 0; list-style: none; }
  .pj-tags li { font-size: 0.7em; color: #494e52; background: #f2f3f3; border-radius: 4px; padding: 2px 8px; margin: 0; }
  .pj-links { font-size: 0.85em; font-weight: 600; margin: 0; }
  .pj-links a { text-decoration: none; margin-right: 1.1em; white-space: nowrap; }
  .pj-links a:hover { text-decoration: underline; }

  /* featured */
  .pj-featured { border: 1px solid #e6e8e9; border-radius: 8px; overflow: hidden; margin-bottom: 1em; }
  .pj-featured img { display: block; width: 100%; height: auto; border-bottom: 1px solid #e6e8e9; }
  .pj-featured .pj-body { padding: 1.2em 1.4em 1.3em; }
  .pj-featured .pj-title { font-size: 1.35em; }
  .pj-featured .pj-text { font-size: 0.95em; }
  .pj-btn { display: inline-block; background: #0077cc; color: #fff !important; border-radius: 6px; padding: 6px 14px; margin-right: 1em; }
  .pj-btn:hover { background: #005999; text-decoration: none !important; }

  /* grid (Sentigrate) */
  .pj-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
  .pj-card { border: 1px solid #e6e8e9; border-radius: 8px; padding: 1.1em 1.2em; display: flex; flex-direction: column; }
  .pj-card .pj-links { margin-top: auto; }
  .pj-card .pj-title { font-size: 1em; }
  .pj-card .pj-text, .pj-row .pj-text { font-size: 0.82em; }
  .pj-row .pj-title { font-size: 1.05em; }

  /* list with thumbnail (research) */
  .pj-row { display: grid; grid-template-columns: 220px 1fr; gap: 1.4em; padding: 1.4em 0; border-top: 1px solid #e6e8e9; }
  .pj-row:last-of-type { border-bottom: 1px solid #e6e8e9; }
  .pj-thumb { border: 1px solid #e6e8e9; border-radius: 6px; background: #fff; aspect-ratio: 4 / 3; display: flex; align-items: center; justify-content: center; overflow: hidden; }
  .pj-thumb img { width: 100%; height: 100%; object-fit: contain; padding: 6px; }

  @media (max-width: 700px) {
    .pj-grid { grid-template-columns: 1fr; }
    .pj-row { grid-template-columns: 1fr; gap: 0.9em; }
    .pj-thumb { max-width: 360px; }
  }
</style>

<p class="pj-intro">A selection of my work: research in medical imaging and wearable sensing at KU Leuven, and applied AI projects at Sentigrate.</p>

<h2 class="pj-section">Featured</h2>

<div class="pj-featured">
  <a href="/projects/retinal-alzheimers/"><img src="/images/projects/retad-graphical-abstract.png" alt="Graphical abstract: 40 participants with PET-confirmed amyloid status, three retinal imaging techniques (hyperspectral imaging, OCT, fundus photography) and classification results"></a>
  <div class="pj-body">
    <p class="pj-meta">KU Leuven · 2024–2025 · Published in Bioengineering, 2026</p>
    <h3 class="pj-title">Multimodal retinal imaging for early Alzheimer's detection</h3>
    <p class="pj-text">Can an eye scan reveal signs of amyloid in the brain before dementia sets in? I built the full pipeline, from image quality control and preprocessing to feature extraction and classification, combining hyperspectral imaging, OCT and fundus photography in 40 participants with PET-confirmed amyloid status. A new hyperspectral texture biomarker, combined with OCT, reached an AUC of 0.84 in this proof-of-concept cohort.</p>
    <ul class="pj-tags"><li>Hyperspectral imaging</li><li>OCT</li><li>Texture biomarkers</li><li>Multimodal classification</li></ul>
    <p class="pj-links">
      <a class="pj-btn" href="/projects/retinal-alzheimers/">Read the story</a>
      <a href="https://www.mdpi.com/2306-5354/13/9/1041">Paper</a>
      <a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/aos.17369">Conference abstract</a>
    </p>
  </div>
</div>

<h2 class="pj-section">Applied AI at Sentigrate</h2>
<p class="pj-section-sub">Data Scientist, since November 2025</p>

<div class="pj-grid">
  <div class="pj-card">
    <p class="pj-meta">Computer vision</p>
    <h3 class="pj-title">SCOPR: AI-assisted building inspection</h3>
    <p class="pj-text">Helps property buyers spot construction defects before they buy. I work on facade crack detection and damage segmentation with DINOv3, and on turning the findings into inspection reports with vision-language models (Gemma 4).</p>
    <ul class="pj-tags"><li>DINOv3</li><li>Segmentation</li><li>VLMs</li></ul>
    <p class="pj-links"><a href="https://www.sentigrate.com/scopr/">Project page →</a></p>
  </div>
  <div class="pj-card">
    <p class="pj-meta">Wearables · with Epihunter</p>
    <h3 class="pj-title">FoG: freezing of gait in Parkinson's</h3>
    <p class="pj-text">Detecting and predicting freezing-of-gait episodes from wearable EEG. The model runs on the device, so it can trigger a sensory cue in real time to help the patient start moving again.</p>
    <ul class="pj-tags"><li>EEG</li><li>Time series</li><li>On-device inference</li></ul>
    <p class="pj-links"><a href="https://www.sentigrate.com/fog/">Project page →</a></p>
  </div>
  <div class="pj-card">
    <p class="pj-meta">Sensor fusion · elderly care</p>
    <h3 class="pj-title">DistriMuSe: activity recognition in care homes</h3>
    <p class="pj-text">Combining wearable IMUs, radar and localisation beacons to recognise activities and flag anomalies, so care staff can act before problems escalate. Includes model compression for deployment on edge hardware.</p>
    <ul class="pj-tags"><li>IMU + radar</li><li>HAR</li><li>Edge AI</li></ul>
    <p class="pj-links"><a href="https://www.sentigrate.com/distrimuse/">Project page →</a></p>
  </div>
  <div class="pj-card">
    <p class="pj-meta">Time series · with Telraam</p>
    <h3 class="pj-title">Anomaly detection in street traffic</h3>
    <p class="pj-text">Telraam's citizen-run sensors count pedestrians, cyclists, cars and heavy vehicles. I use Chronos2, a time-series foundation model, to detect anomalies in these counts and help communities understand their local traffic.</p>
    <ul class="pj-tags"><li>Chronos2</li><li>Foundation models</li><li>Anomaly detection</li></ul>
    <p class="pj-links"><a href="https://telraam.net">Telraam →</a></p>
  </div>
</div>

<h2 class="pj-section">Research at KU Leuven</h2>
<p class="pj-section-sub">Research Group Ophthalmology &amp; ESAT-STADIUS, and master's theses</p>

<div class="pj-row">
  <div class="pj-thumb"><img src="/images/projects/glaucoma-umap.png" alt="UMAP of image embeddings coloured by dataset and label, showing domain shift between glaucoma datasets" loading="lazy"></div>
  <div>
    <p class="pj-meta">KU Leuven · 2024–2025</p>
    <h3 class="pj-title">Vision foundation models for glaucoma classification</h3>
    <p class="pj-text">Glaucoma classifiers often break down when moved to a new camera, clinic or population. I fine-tuned self-supervised vision foundation models on multiple source datasets and applied domain adaptation to make classification robust to these shifts.</p>
    <ul class="pj-tags"><li>Foundation models</li><li>Self-supervised learning</li><li>Domain adaptation</li></ul>
    <p class="pj-links"><a href="https://github.com/MichielGhesquiere/glaucoma">Code →</a></p>
  </div>
</div>

<div class="pj-row">
  <div class="pj-thumb"><img src="/images/projects/seizure-wearables.png" alt="Schematic of wearable EEG, EMG and accelerometer sensors used for seizure detection" loading="lazy"></div>
  <div>
    <p class="pj-meta">MSc Artificial Intelligence thesis · 2023</p>
    <h3 class="pj-title">Seizure detection from multimodal wearables</h3>
    <p class="pj-text">An automatic seizure detection algorithm for people with epilepsy, using wearable EEG, EMG and accelerometer data. Features are extracted per modality and classified with an SVM. Combining modalities improved sensitivity and reduced false alarms.</p>
    <ul class="pj-tags"><li>EEG / EMG / ACC</li><li>Sensor fusion</li><li>SVM</li></ul>
    <p class="pj-links"><a href="https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9993576486601488&amp;context=L&amp;vid=32KUL_KUL:KULeuven&amp;lang=en&amp;search_scope=All_Content&amp;adaptor=Local%20Search%20Engine&amp;tab=all_content_tab&amp;query=any,contains,michiel%20ghesquiere">Thesis →</a></p>
  </div>
</div>

<div class="pj-row">
  <div class="pj-thumb"><img src="/images/projects/hens-pipeline.png" alt="Overview of the hybrid algorithm combining YOLOv5 head detection with motion detection" loading="lazy"></div>
  <div>
    <p class="pj-meta">MSc Bioscience Engineering thesis · 2022</p>
    <h3 class="pj-title">Camera-based behaviour monitoring of laying hens</h3>
    <p class="pj-text">Early detection of behaviour linked to poultry red mite infestation in individual hens. A YOLOv5 head detector, fine-tuned on a custom-labelled dataset, is combined with Gaussian mixture model motion detection.</p>
    <ul class="pj-tags"><li>Object detection</li><li>Motion analysis</li><li>Animal welfare</li></ul>
    <p class="pj-links">
      <a href="https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9993097125501488&amp;context=L&amp;vid=32KUL_KUL:KULeuven&amp;lang=en&amp;search_scope=All_Content&amp;adaptor=Local%20Search%20Engine&amp;tab=all_content_tab&amp;query=any,contains,michiel%20ghesquiere">Thesis →</a>
      <a href="https://kuleuven.limo.libis.be/discovery/fulldisplay?docid=alma9994277629301488&amp;context=L&amp;vid=32KUL_KUL:KULeuven&amp;lang=en&amp;search_scope=All_Content&amp;adaptor=Local%20Search%20Engine&amp;tab=all_content_tab&amp;query=any,contains,michiel%20ghesquiere">Publication →</a>
      <a href="/images/YOLO_chicken_head_clipped.mp4">Demo video →</a>
    </p>
  </div>
</div>
