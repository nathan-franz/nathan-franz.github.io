---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
entries_layout: grid
show_teaser: true
---

You can also find my published work on [my Google Scholar profile](https://scholar.google.com/citations?user=lNA1JsMAAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
