---
layout: archive
title: "Main Projects"
permalink: /research/
author_profile: false
---
{% include base_path %}

<div class="grid">
  <div class="wrapper">
    {% for post in site.research %}
      {% include archive-single-proj.html %}
    {% endfor %}
  </div>
</div>

