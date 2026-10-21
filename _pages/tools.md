---
layout: page
title: Tools
permalink: /tools/
description: Tools built and run by the Donghyun Lee AI Group.
nav: true
nav_order: 6
---

<div class="container mt-3">
  <p class="text-muted mb-5">
    Tools built and run by our group. Each entry says what it covers and where its data come from.
  </p>

  <div class="card mb-4 z-depth-1">
    <div class="row g-0">
      <div class="col-md-5">
        <a href="https://hpai.kr">
          <img src="{{ '/assets/img/tools/hpai-dashboard-en.jpg' | relative_url }}" class="img-fluid rounded-start"
            alt="HPAI Dashboard: map of South Korea showing county-level HPAI detection likelihood">
        </a>
      </div>
      <div class="col-md-7">
        <div class="card-body p-4">
          <h4 class="fw-bold mb-2">HPAI Dashboard (hpai.kr)</h4>
          <span class="badge bg-secondary mb-3">Korean &amp; English</span>
          <p class="text-secondary mb-3">
            HPAI Dashboard (hpai.kr), run by the Donghyun Lee AI Group, shows highly pathogenic avian
            influenza outbreaks in South Korea and worldwide on maps and season comparisons. For wild
            birds in Korea, it also estimates this season's detections, when the first detection may come,
            and the likelihood for each city and county.
          </p>
          <p class="text-muted small mb-3">
            <i class="fas fa-database me-1"></i>
            Data from WADIS (NIWDC), MAFRA outbreak records, WOAH WAHIS and Open-Meteo.
            It does not replace official government announcements.
          </p>
          <a class="btn btn-sm btn-outline-primary" href="https://hpai.kr">Visit dashboard →</a>
        </div>
      </div>
    </div>
  </div>
</div>
