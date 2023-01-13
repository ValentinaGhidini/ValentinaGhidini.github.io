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




**Published**

* Ghidini, V., Perotti, A., Schifanella, R. (2019)
**Quantitative and Ontology-Based Comparison of Explanations for Image Classification.**
*Machine Learning, Optimization, and Data Science. LOD 2019. Lecture Notes in Computer Science, vol 11943. Springer, 2019* ([pdf]({{ site.baseurl }}/files/LOD_Final.pdf)).

**Submitted/Under Review**

* &#9733; Borgonovo, E., Ghidini, V., Hahn, R., Plischke, E. (2021+) 
**Post-hoc Explanations through Probabilistic Sensitivity Measures.**
*Submitted*.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



&#9733; Authors in alphabetical order

