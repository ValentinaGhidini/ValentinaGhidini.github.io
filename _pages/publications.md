---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Under Review:

<ul>
  <li>Post-hoc Explanations through Probabilistic Sensitivity Measures, joint work with E. Borgonovo et al. (2021+)</li>
 
</ul>
