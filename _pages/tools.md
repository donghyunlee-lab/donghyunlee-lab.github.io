---
layout: page
title: Tools
permalink: /tools/
description: Public tools operated by the Donghyun Lee AI Group.
nav: true
nav_order: 6
---

<div class="container mt-3">
  <p class="text-muted mb-5">
    Tools we run for public use. Each entry says what it covers, where its data come from,
    and how it reports uncertainty.
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
          <span class="badge bg-secondary mb-3">Non-commercial · Korean &amp; English</span>
          <p class="text-secondary mb-3">
            HPAI Dashboard (hpai.kr) is a non-commercial avian influenza dashboard operated by the
            Donghyun Lee AI Group. It tracks highly pathogenic avian influenza in South Korea and
            worldwide from public sources, updated twice daily in Korean and English. Daily forecasts
            are archived without revision, with timestamped evidence of when they were issued.
          </p>
          <p class="text-muted small mb-3">
            <i class="fas fa-database me-1"></i>
            Public data from WADIS (NIWDC), MAFRA outbreak records, WOAH WAHIS and Open-Meteo.
            It does not replace official government announcements.
          </p>
          <a class="btn btn-sm btn-outline-primary" href="https://hpai.kr">Visit dashboard →</a>
        </div>
      </div>
    </div>
  </div>
</div>
