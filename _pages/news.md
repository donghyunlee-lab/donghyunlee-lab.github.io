---
layout: page
title: News
permalink: /news/
description: Talks, awards, papers, and lab events.
nav: true
nav_order: 5
---

{% include news.liquid %}

{% comment %} Photos: standalone photos from \_data/gallery.yml, then photos from news posts that have an `img:` field. This section replaced the old Gallery page (/gallery/ now redirects here). {% endcomment %}
{% assign extra_photos = "" | split: "" %}
{% if site.data.gallery %}
{% assign extra_photos = site.data.gallery | where_exp: "item", "item.image" | sort: "date" | reverse %}
{% endif %}
{% assign news_photos = site.news | where_exp: "item", "item.img" | sort: "date" | reverse %}
{% assign photo_count = extra_photos.size | plus: news_photos.size %}
{% if photo_count > 0 %}

<h2 id="photos" class="h3 mt-5 mb-4">Photos</h2>

<div class="row">
  {% for item in extra_photos %}
    <div class="col-sm-6 col-lg-4 mb-4">
      {% if item.url %}<a href="{{ item.url }}" class="text-decoration-none">{% endif %}
      <div class="card h-100 z-depth-1 gallery-card">
        {% include figure.liquid loading="lazy" path=item.image class="card-img-top gallery-img" alt="" %}
        {% if item.caption or item.date %}
          <div class="card-body p-3">
            {% if item.caption %}<h3 class="h6 card-title mb-1">{{ item.caption | emojify }}</h3>{% endif %}
            {% if item.date %}<p class="card-text text-muted small mb-0">{{ item.date | date: '%b %d, %Y' }}</p>{% endif %}
          </div>
        {% endif %}
      </div>
      {% if item.url %}</a>{% endif %}
    </div>
  {% endfor %}
  {% for item in news_photos %}
    <div class="col-sm-6 col-lg-4 mb-4">
      <a href="{{ item.url | relative_url }}" class="text-decoration-none">
        <div class="card h-100 z-depth-1 gallery-card">
          {% include figure.liquid loading="lazy" path=item.img class="card-img-top gallery-img" alt="" %}
          <div class="card-body p-3">
            <h3 class="h6 card-title mb-1">{{ item.title | emojify }}</h3>
            <p class="card-text text-muted small mb-0">{{ item.date | date: '%b %d, %Y' }}</p>
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
</div>
{% endif %}
