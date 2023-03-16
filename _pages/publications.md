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




**Refereed Journals**

* Borgonovo, E., **Ghidini, V.**, Hahn, R., Plischke, E. &#9733; (2023) 
*Explaining Classifiers with Measures of Statistical Association*,  Computational Statistics \& Data Analysis,
forthcoming.


**Conference Proceedings**

* **Ghidini, V.**, Legramanti, S., Argiento, R. (2023), Extended Stochastic Block Model with Spatial Covariates for Weighted Brain Networks. Bayesian Statistics, New Generations New Approaches (BAYSM2022), forthcoming.

* **Ghidini, V.**, Perotti, A., Schifanella, R. (2019)
*Quantitative and Ontology-Based Comparison of Explanations for Image Classification.*
Lecture Notes in Computer Science 11943, 58-70. ([pdf]({{ site.baseurl }}/files/LOD_Final.pdf)).


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



&#9733; Authors in alphabetical order

