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

  /* slider (Sentigrate) */
  .pj-slider { position: relative; }
  .pj-track { display: flex; overflow-x: auto; scroll-snap-type: x mandatory; scroll-behavior: smooth; scrollbar-width: none; gap: 16px; border-radius: 8px; }
  .pj-track::-webkit-scrollbar { display: none; }
  .pj-track:focus-visible { outline: 2px solid #0077cc; outline-offset: 4px; }
  .pj-card { flex: 0 0 100%; scroll-snap-align: start; border: 1px solid #e6e8e9; border-radius: 8px; padding: 1.6em 1.8em 1.5em; background: #fff; display: flex; flex-direction: column; min-height: 15em; }
  .pj-card .pj-title { font-size: 1.25em; }
  .pj-card .pj-text { font-size: 0.92em; max-width: 40em; }
  .pj-card .pj-links { margin-top: auto; }
  .pj-card .pj-meta { display: flex; justify-content: space-between; gap: 1em; }
  .pj-count { font-weight: 500; letter-spacing: 0.04em; color: #9ca1a5; }
  .pj-nav { display: flex; align-items: center; justify-content: center; gap: 18px; margin-top: 16px; }
  .pj-arrow { width: 36px; height: 36px; border-radius: 50%; border: 1px solid #e6e8e9; background: #fff; color: #494e52; font-size: 18px; line-height: 1; cursor: pointer; display: flex; align-items: center; justify-content: center; padding: 0; }
  .pj-arrow:hover:not(:disabled) { border-color: #0077cc; color: #0077cc; }
  .pj-arrow:disabled { opacity: 0.35; cursor: default; }
  .pj-dots { display: flex; gap: 8px; align-items: center; }
  .pj-dot { width: 10px; height: 10px; border-radius: 999px; border: 0; padding: 0; background: #d5d8da; cursor: pointer; transition: width 0.25s, background 0.25s; }
  .pj-dot[aria-current="true"] { width: 30px; background: #0077cc; }

  /* list with thumbnail (research) */
  .pj-row { display: grid; grid-template-columns: minmax(0, 5fr) minmax(0, 6fr); gap: 1.6em; align-items: start; padding: 1.4em 0; border-top: 1px solid #e6e8e9; }
  .pj-row:last-of-type { border-bottom: 1px solid #e6e8e9; }
  .pj-thumb { border: 1px solid #e6e8e9; border-radius: 6px; background: #fff; aspect-ratio: 3 / 2; display: flex; align-items: center; justify-content: center; overflow: hidden; }
  .pj-thumb img { width: 100%; height: 100%; object-fit: contain; padding: 8px; }

  @media (max-width: 700px) {
    .pj-card { padding: 1.2em 1.2em; }
    .pj-row { grid-template-columns: 1fr; gap: 0.9em; }
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

{%- assign sg = site.data.sentigrate_projects -%}
<div class="pj-slider" data-slider>
<div class="pj-track" tabindex="0" aria-label="Sentigrate projects, use arrow keys or swipe to browse">
{%- for p in sg -%}{%- include project-card.html p=p i=forloop.index n=forloop.length -%}{%- endfor -%}
</div>
<div class="pj-nav">
<button class="pj-arrow" type="button" data-prev aria-label="Previous project">←</button>
<div class="pj-dots">{%- for p in sg -%}<button class="pj-dot" type="button" aria-label="Show {{ p.title | escape }}"></button>{%- endfor -%}</div>
<button class="pj-arrow" type="button" data-next aria-label="Next project">→</button>
</div>
</div>

<script>
(function () {
  var root = document.querySelector('[data-slider]');
  if (!root) return;
  var track = root.querySelector('.pj-track');
  var cards = track.children;
  var dots = root.querySelectorAll('.pj-dot');
  var prev = root.querySelector('[data-prev]');
  var next = root.querySelector('[data-next]');
  function go(i) {
    i = Math.max(0, Math.min(cards.length - 1, i));
    track.scrollTo({ left: i * (cards[0].offsetWidth + 16), behavior: 'smooth' });
  }
  function update() {
    var i = Math.min(cards.length - 1, Math.round(track.scrollLeft / (cards[0].offsetWidth + 16)));
    for (var d = 0; d < dots.length; d++) dots[d].setAttribute('aria-current', d === i ? 'true' : 'false');
    prev.disabled = i === 0;
    next.disabled = i === cards.length - 1;
    root.dataset.index = i;
  }
  prev.addEventListener('click', function () { go(+root.dataset.index - 1); });
  next.addEventListener('click', function () { go(+root.dataset.index + 1); });
  for (var d = 0; d < dots.length; d++) (function (d) { dots[d].addEventListener('click', function () { go(d); }); })(d);
  track.addEventListener('keydown', function (e) {
    if (e.key === 'ArrowRight') { e.preventDefault(); go(+root.dataset.index + 1); }
    if (e.key === 'ArrowLeft') { e.preventDefault(); go(+root.dataset.index - 1); }
  });
  var t; track.addEventListener('scroll', function () { clearTimeout(t); t = setTimeout(update, 60); });
  window.addEventListener('resize', update);
  update();
})();
</script>

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
