---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{author.googlescholar}">my Google Scholar profile</a>.</u>
{% endif %}

<<<<<<< HEAD
{{author.googlescholar}}
{author.googlescholar}
author.googlescholar
=======
"{{author.googlescholar}}"
>>>>>>> ed4c7a491425363e8f07afc7af85d5649d67d6c8

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
