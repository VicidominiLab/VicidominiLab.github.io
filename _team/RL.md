---
title: "Romain Laine"
collection: team
header:
  teaser: RL.jpg
tags: post-doc
tagline: Postdoc
date: 2020-02-21
email: 'r.laine@ucl.ac.uk'
---

<!-- {::options parse_block_html="true" /} -->

<p align= "justify">

I am interested in developing and applying advanced microscopy techniques to decipher functional and structural organisation of life at multiple scales. For this, I develop analytical and optical tools.

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Laine" %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}