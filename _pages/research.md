---
layout: page
title: Research
permalink: /research/
description: Our research questions, funded projects, the hpai.kr dashboard, and code.
nav: true
nav_order: 3
---

<p class="lead research-intro">
  We study AI that forecasts algal blooms and disease outbreaks, and language models that answer
  surveys in place of people. Does a model hold up in new places and years
  (<strong>Reliability</strong>)? Do people and agencies act on it (<strong>Trust</strong>)? Does
  their trust match its accuracy (<strong>Calibration</strong>)?
</p>

<h2 id="projects" class="h3 mt-5 mb-4">Projects</h2>

<h3 class="h5 text-muted mb-3">Current</h3>
<div class="list-group mb-4 research-projects">
  <div class="list-group-item w-100 flex-column align-items-start p-4">
    <div class="d-flex w-100 justify-content-between">
      <h4 class="h5 mb-1 font-weight-bold"><a class="stretched-link" href="{{ '/research/disaster-response/' | relative_url }}">Ultra-Fast Physics-AI Hybrid Disaster Response Based on MambaFlow Matching <span class="rp-arrow" aria-hidden="true">→</span></a></h4>
      <small class="text-muted">2026 – 2033</small>
    </div>
    <p class="mb-1 mt-2">Development of an ultra-fast, high-reliability physics-AI hybrid disaster response technology based on MambaFlow matching.</p>
    <small class="text-primary"><i class="fas fa-building" aria-hidden="true"></i> Funded by IITP (Institute of Information &amp; Communications Technology Planning &amp; Evaluation)</small>
    <small class="lab-role"> · Principal Investigator</small>
  </div>

  <div class="list-group-item w-100 flex-column align-items-start p-4">
    <div class="d-flex w-100 justify-content-between">
      <h4 class="h5 mb-1 font-weight-bold"><a class="stretched-link" href="{{ '/research/algal-bloom/' | relative_url }}">Physics-AI Integrated Dynamic Graph Meta-Learning for Algal Bloom Prediction <span class="rp-arrow" aria-hidden="true">→</span></a></h4>
      <small class="text-muted">2026 – 2029</small>
    </div>
    <p class="mb-1 mt-2">Development of physics-AI integrated dynamic graph meta-learning based algal bloom prediction technology for overcoming data scarcity.</p>
    <small class="text-primary"><i class="fas fa-building" aria-hidden="true"></i> Funded by National Research Foundation of Korea (NRF)</small>
    <small class="lab-role"> · Principal Investigator</small>
  </div>
</div>

<h3 class="h5 text-muted mb-3">Completed</h3>
<div class="list-group research-projects">
  <div class="list-group-item w-100 flex-column align-items-start p-4">
    <div class="d-flex w-100 justify-content-between">
      <h4 class="h5 mb-1 font-weight-bold"><a class="stretched-link" href="{{ '/research/wild-bird-avian-influenza/' | relative_url }}">Wild Bird Avian Influenza Spread Prediction Research (I–III) <span class="rp-arrow" aria-hidden="true">→</span></a></h4>
      <small class="text-muted">2023 – 2026</small>
    </div>
    <p class="mb-1 mt-2">Developed spatial spread prediction models using machine learning.</p>
    <small class="text-primary"><i class="fas fa-building" aria-hidden="true"></i> Funded by National Institute of Wildlife Disease Control and Prevention (NIWDCP)</small>
    <small class="lab-role"> · Principal Investigator (I–II), Co‑Investigator (III)</small>
  </div>

  <div class="list-group-item w-100 flex-column align-items-start p-4">
    <div class="d-flex w-100 justify-content-between">
      <h4 class="h5 mb-1 font-weight-bold"><a class="stretched-link" href="{{ '/research/infectious-disease-transfer-learning/' | relative_url }}">Simulation of Infectious Disease Prediction Using Transfer Learning Deep Learning <span class="rp-arrow" aria-hidden="true">→</span></a></h4>
      <small class="text-muted">2020 – 2025</small>
    </div>
    <p class="mb-1 mt-2">Long-term research on AI-based infectious disease modeling and transfer learning applications.</p>
    <small class="text-primary"><i class="fas fa-building" aria-hidden="true"></i> Funded by National Research Foundation of Korea (NRF)</small>
    <small class="lab-role"> · Principal Investigator</small>
  </div>
</div>

<div class="text-center mt-4">
  <a href="{{ '/professor/' | relative_url }}" class="btn btn-outline-dark">
    <i class="fas fa-user-tie mr-2" aria-hidden="true"></i> View Full Project List on PI's Profile
  </a>
</div>

<h2 id="dashboard" class="h3 mt-5 mb-4">Dashboard</h2>

<div class="card mb-4 z-depth-1 tool-card">
  <div class="row no-gutters">
    <div class="col-md-5 tool-img">
      <a href="https://hpai.kr">
        <img src="{{ '/assets/img/tools/hpai-dashboard-en.jpg' | relative_url | bust_file_cache }}" class="img-fluid"
          alt="HPAI Dashboard: map of South Korea shaded by the chance of detection in each city and county">
      </a>
    </div>
    <div class="col-md-7">
      <div class="card-body p-4">
        <h3 class="h4 font-weight-bold mb-2">HPAI Dashboard (hpai.kr)</h3>
        <span class="badge lab-tag mb-3">Korean &amp; English</span>
        <p class="mb-3">
          HPAI Dashboard (hpai.kr), run by the Donghyun Lee AI Group, shows highly pathogenic avian
          influenza outbreaks in South Korea and worldwide on maps and season comparisons. For wild
          birds in Korea, it also forecasts how many detections this season will have, when the first
          detection may come, and the chance of detection in each city and county.
        </p>
        <p class="text-muted small mb-3">
          <i class="fas fa-info-circle mr-1" aria-hidden="true"></i>
          It does not replace official government announcements.
        </p>
        <a class="btn btn-sm btn-outline-primary" href="https://hpai.kr">Visit dashboard →</a>
      </div>
    </div>
  </div>
</div>

<h2 id="code" class="h3 mt-5 mb-3">Code</h2>
<p class="mb-4">We publish the code behind our papers so others can check and rerun the results.</p>

<div class="card mb-4 z-depth-1">
  <div class="card-body p-4">
    <div class="d-flex justify-content-between align-items-start flex-wrap">
      <h3 class="h4 font-weight-bold mb-2">Hybrid Chlorophyll-a Forecast</h3>
      <span class="badge lab-tag align-self-center mb-2">MIT · CC BY 4.0</span>
    </div>

    <p class="mb-3">
      Code, daily monitoring data, and result tables for <em>"Hard constraints
      make an accurate hybrid chlorophyll-a forecast interpretable: a process
      equation with an xLSTM correction."</em> Across 27 monitoring stations in
      South Korea's four major river basins (2024–2025), the model embeds a
      five-constant Gompertz-type process equation in ln Chl-a inside physical
      intervals, adds a bounded cross-basin xLSTM daily correction, and
      evaluates 1, 3, 7, and 14-day forecasts against 21 other single models and
      a six-model mean. Every forecast splits into exact additive process terms,
      and scripts support three reproducibility levels from rebuilding all paper
      tables and figures on CPU to full retraining.
    </p>

    <p class="text-muted small mb-3">
      <i class="fas fa-database mr-1" aria-hidden="true"></i>
      Ships compiled daily water-quality and algae-alert observations from
      Korea's Water Environment Information System
      (<a href="https://water.nier.go.kr" target="_blank" rel="noopener">water.nier.go.kr</a>,
      NIER) and daily ERA5 weather series via Open-Meteo
      (<a href="https://open-meteo.com" target="_blank" rel="noopener">open-meteo.com</a>);
      saved forecasts and model files (about 730 MB) are archived on Zenodo, and
      GIS shapefiles for Figure 1 are obtained from their providers.
    </p>

    <a href="https://github.com/donghyunlee-lab/chla-hybrid-forecast"
       class="btn btn-outline-dark btn-sm" target="_blank" rel="noopener">
      <i class="fab fa-github mr-1" aria-hidden="true"></i> View on GitHub
    </a>
    <a href="https://doi.org/10.5281/zenodo.24470518"
       class="btn btn-outline-dark btn-sm" target="_blank" rel="noopener">
      <i class="ai ai-doi mr-1" aria-hidden="true"></i> Zenodo archive
    </a>

    <p class="text-muted small mt-3 mb-0">
      <i class="fas fa-hand-holding-usd mr-1" aria-hidden="true"></i>
      Supported by IITP (RS-2026-25522834, Physics-AI Hybrid Disaster Response
      Technology).
    </p>

  </div>
</div>

<div class="card mb-4 z-depth-1">
  <div class="card-body p-4">
    <div class="d-flex justify-content-between align-items-start flex-wrap">
      <h3 class="h4 font-weight-bold mb-2">Synthetic-Panel Audit</h3>
      <span class="badge lab-tag align-self-center mb-2">Apache-2.0 · CC BY 4.0</span>
    </div>

    <p class="mb-3">
      Audit protocol and benchmark for <em>"Everyone's taste and no one's: an
      audit protocol for LLM synthetic panels in UX research."</em> Each of
      18,448 LabintheWild participants is paired with a persona-conditioned
      digital twin that rates the same websites, yielding about 620,000
      synthetic ratings across five model families, audited against a noise
      ceiling from human re-ratings. The package ships the audit code, the
      full synthetic-rating data, a demographic-oracle bound, and a screening
      rule that identifies in advance the populations for which a synthetic
      panel should be refused.
    </p>

    <p class="text-muted small mb-3">
      <i class="fas fa-database mr-1" aria-hidden="true"></i>
      The LabintheWild human anchor (CC BY-NC-SA 3.0, Reinecke &amp; Gajos,
      CHI 2014) is not redistributed; a download script fetches it from the
      original authors' site.
    </p>

    <a href="https://github.com/donghyunlee-lab/synthetic-panel-audit"
       class="btn btn-outline-dark btn-sm" target="_blank" rel="noopener">
      <i class="fab fa-github mr-1" aria-hidden="true"></i> View on GitHub
    </a>
    <a href="https://doi.org/10.5281/zenodo.22080775"
       class="btn btn-outline-dark btn-sm" target="_blank" rel="noopener">
      <i class="ai ai-doi mr-1" aria-hidden="true"></i> Zenodo archive
    </a>

  </div>
</div>

<div class="card mb-4 z-depth-1">
  <div class="card-body p-4">
    <div class="d-flex justify-content-between align-items-start flex-wrap">
      <h3 class="h4 font-weight-bold mb-2">ACES — Adaptive Conformal Early-warning System</h3>
      <span class="badge lab-tag align-self-center mb-2">MIT License</span>
    </div>

    <p class="mb-3">
      Reproduction code for <em>"Calibration, not loss design, governs
      prediction-interval quality: an adaptive conformal early-warning system
      for algal-bloom forecasting."</em> The benchmark crosses five
      heteroscedastic loss families with three forecasting backbones (Mamba,
      GRU, inverted Transformer), pairs every predictor with raw,
      split-conformal, and online adaptive-conformal calibration, and evaluates
      an early-warning decision layer on the calibrated intervals. The central
      finding: the calibration layer — not the training loss — governs
      prediction-interval quality under distribution shift.
    </p>

    <p class="text-muted small mb-3">
      <i class="fas fa-database mr-1" aria-hidden="true"></i>
      Uses publicly available observations from the Korean national
      water-quality monitoring network
      (<a href="https://water.nier.go.kr" target="_blank" rel="noopener">water.nier.go.kr</a>),
      Geum River basin, 2021–2024. Raw records are not redistributed; see the
      repository README for the preprocessing pipeline.
    </p>

    <a href="https://github.com/donghyunlee-ai/aces-hab-forecasting"
       class="btn btn-outline-dark btn-sm" target="_blank" rel="noopener">
      <i class="fab fa-github mr-1" aria-hidden="true"></i> View on GitHub
    </a>

    <p class="text-muted small mt-3 mb-0">
      <i class="fas fa-hand-holding-usd mr-1" aria-hidden="true"></i>
      Supported by IITP (RS-2026-25522834, Physics-AI Hybrid Disaster Response
      Technology), NRF (RS-2026-25493931), and the Hankuk University of Foreign
      Studies Research Fund of 2026.
    </p>

  </div>
</div>

<h2 id="collaboration" class="h3 mt-5 mb-3">Collaboration</h2>
<div class="lab-contact-box mb-5">
  <p class="mb-2">We welcome joint research with universities, research institutes, and public agencies, and questions from prospective Master's and Ph.D. students.</p>
  <p class="mb-0">
    <i class="fas fa-envelope mr-2" aria-hidden="true"></i>Email Prof. Lee at
    <a href="mailto:donghyun.lee@hufs.ac.kr">donghyun.lee [at] hufs.ac.kr</a>.
  </p>
</div>
