---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<!-- 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

My research vision is centered on developing trustworthy and reliable AI systems, aiming to support the advancement of technology and solve social challenges.

<img src="/images/responsibility.png" alt="Responsibility in Machine Learning" width="300" height="200">

*Responsibility in Machine Learning*



{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single-research.html%}
{% endfor %}
