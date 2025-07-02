---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
show_teaser: true
---

You can also find my published work on [my Google Scholar profile](https://scholar.google.com/citations?user=lNA1JsMAAAAJ).

{% for paper in site.research %}
  <div class="paper-block">
    {% if paper.image %}
      <a href="{{ paper.url | relative_url }}">
        <img class="paper-thumb" src="{{ paper.image | relative_url }}" alt="{{ paper.title }}">
      </a>
    {% endif %}
    <h3><a href="{{ paper.url | relative_url }}">{{ paper.title }}</a></h3>
    <p>{{ paper.excerpt }}</p>
  </div>
{% endfor %}
