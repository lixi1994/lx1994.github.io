---
layout: archive
title: Check out my adventures
permalink: /explorations/
author_profile: true
---

{% for exploration in site.explorations %}
  <div class="exploration-category">
    <a href="{{ exploration.url | prepend: site.baseurl }}">
      <!-- <img src="{{ adventure.image }}" alt="{{ adventure.title }}"> -->
      <img src="{{ exploration.image }}" alt="{{ exploration.title }}" style="width: 300px; height: 400px;">
      <figcaption>{{ exploration.title }}</figcaption>
    </a>
  </div>
{% endfor %}

