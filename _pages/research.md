---
layout: archive
title: "Main Projects"
permalink: /research/
author_profile: true
---
{% include base_path %}

{% for post in site.research %}
{% include archive-single-proj-new.html type="grid" %}

{% endfor %}
