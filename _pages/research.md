---
layout: archive
title: "Main Projects"
permalink: /research/
author_profile: true
---
{% include base_path %}

{% for post in site.research %}
{% include archive-single-proj-new.html %}

{% endfor %}

<!--<div class="grid">
  <div class="wrapper">
    {% for post in site.research %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>--->
