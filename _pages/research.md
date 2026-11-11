---
layout: page
title: Research
permalink: /research/
description: Academic research in NLP, brain–language alignment, multimodal learning, and healthcare AI.
nav: true
nav_order: 1
---

<div class="page-intro research">
  <p class="page-label">Research</p>
  <p>Investigating how language models represent meaning, how this relates to human cognition, and how AI can advance healthcare. My work bridges computational linguistics, neuroscience, and applied machine learning.</p>
</div>

<div class="content-section">
  <h2>Research Interests</h2>

  <div class="interest-grid">
    <div class="interest-card">
      <h4>Natural Language Processing</h4>
      <p>Semantic evaluation, clinical NLP, and computational approaches to language understanding — including shared task systems for word sense disambiguation and biomedical inference.</p>
    </div>
    <div class="interest-card">
      <h4>Brain–LLM Alignment</h4>
      <p>Studying how large language models encode linguistic information compared to the human brain, using fMRI data and encoding models to measure representational similarity.</p>
    </div>
    <div class="interest-card">
      <h4>Multimodal Learning</h4>
      <p>Combining vision and language modalities — from CLIP-based visual word sense disambiguation to multimodal medical imaging analysis.</p>
    </div>
    <div class="interest-card">
      <h4>Healthcare AI</h4>
      <p>Applying deep learning to medical imaging (lung ultrasound, chest X-ray) and investigating explainability of AI systems in clinical settings.</p>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Research Experience</h2>

  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-title">Research Fellow</h3>
        <span class="timeline-year">2025 – 2026</span>
      </div>
      <p class="timeline-org">Department of Information Engineering and Computer Science, University of Trento, Italy</p>
      <div class="timeline-desc">
        <ul>
          <li>Investigating lung ultrasound images using deep learning techniques</li>
          <li>Enhancing explainability of LLMs using XAI techniques in the medical domain</li>
          <li>Supervised by <a href="https://webapps.unitn.it/du/it/Persona/PER0204546/Curriculum">Prof. Giovanni Iacca</a></li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-title">Research Assistant</h3>
        <span class="timeline-year">2024 – 2026</span>
      </div>
      <p class="timeline-org">Center for Mind and Brain (CIMeC), University of Trento, Rovereto, Italy</p>
      <div class="timeline-desc">
        <ul>
          <li>Investigated the alignment between brain activation data and large language model representations</li>
          <li>Worked with fMRI data and encoding models to study how linguistic properties affect brain–LLM alignment</li>
          <li>Supervised by <a href="https://webapps.unitn.it/du/it/Persona/PER0001015/Curriculum">Prof. Roberto Zamparelli</a></li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-title">Research Trainee</h3>
        <span class="timeline-year">2022</span>
      </div>
      <p class="timeline-org">University of Groningen, Groningen, The Netherlands</p>
      <div class="timeline-desc">
        <ul>
          <li>Conducted research during master's program in computational linguistics and NLP</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Selected Publications</h2>

  <p>See the full <a href="/publications/">publications page</a> for all papers with abstracts, BibTeX, and links.</p>

  <div class="publications" style="margin-top: 1rem;">
    {% bibliography --group_by none --query @*[selected=true]* %}
  </div>
</div>

<div class="content-section">
  <h2>Research Projects</h2>

  <div style="margin-top: 1rem;">
    <p><strong>Brain–LLM Alignment</strong> — Investigating how removing different linguistic properties (syntax, semantics) affects the alignment between language models and brain responses measured via fMRI. Training LSTM and GPT-2 models on distorted corpora and comparing representational alignment.</p>

    <p><strong>Visual Word Sense Disambiguation</strong> (SemEval-2023) — Developed a system combining WordNet-based text augmentation with CLIP and ViLT multimodal models for image disambiguation. Ranked 16th for English.</p>

    <p><strong>Clinical NLP Inference</strong> (SemEval-2024) — Investigated generative and discriminative LLMs for determining entailment/contradiction between clinical trial records and statements. DeBERTa-lg achieved 4th place on the leaderboard.</p>

    <p><strong>Chest X-ray Abnormality Detection</strong> — Ensemble of deep convolutional neural networks for localizing abnormalities in chest X-ray images.</p>
  </div>
</div>

<div class="content-section">
  <h2>Education</h2>

  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-title">Joint Master's Degree in Language and Communication Technologies</h3>
        <span class="timeline-year">2021 – 2023</span>
      </div>
      <p class="timeline-org">University of Groningen, The Netherlands &amp; University of Trento, Italy</p>
      <div class="timeline-desc">
        Erasmus Mundus Joint Master's Degree. Research Master's in Linguistics (Groningen) and MSc in Cognitive Science (Trento).
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-title">BSc in Computer Science and Engineering</h3>
        <span class="timeline-year">2014 – 2018</span>
      </div>
      <p class="timeline-org">University of Chittagong, Bangladesh</p>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Honors &amp; Awards</h2>

  <ul>
    <li><strong>Erasmus Mundus Scholarship</strong> (2021) — Full scholarship for the LCT joint master's program</li>
    <li><strong>NASA Space Apps Challenge — Global Finalist</strong> (2019) — Selected among global finalists</li>
  </ul>
</div>
