---
layout: plain
title: Constellations
description: >
  These are external resources that are recommended for technical proficiency,
  minimal design, and deep thought.
hide_description: false
---

<div class="constellation-cards">
{% for link in site.data.constellations %}
<a href="{{ link.url }}" class="constellation-card no-mark external" target="_blank" rel="noopener">
  <div class="constellation-card-body">
    <div class="constellation-card-title">{{ link.title }}</div>
    <div class="constellation-card-desc">{{ link.description }}</div>
    <div class="constellation-card-meta">
      <img src="https://www.google.com/s2/favicons?domain={{ link.url | split: '//' | last | split: '/' | first }}&sz=32"
           alt="" width="16" height="16" class="constellation-card-favicon" loading="lazy">
      <span>{{ link.site_name }}</span>
    </div>
  </div>
  {% if link.image %}
  <img src="{{ link.image }}" alt="" class="constellation-card-image" loading="lazy">
  {% endif %}
</a>
{% endfor %}
</div>

---

## Badges
<div class="badge-wall" role="list" aria-label="Site badges">
  <img src="/assets/img/constellation.png" alt="KyleOBrien.me" width="88" height="31">
</div>

Want to trade badges? Reach out via any link in the sidebar.
