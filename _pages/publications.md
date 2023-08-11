---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Mainly Work

· Kong M, Su R, Zhao S, et al. DEPHN: Different Expression Parallel Heterogeneous Network using virtual gradient optimization for Multi-task Learning[C]//2023 International Joint Conference on Neural Networks (IJCNN). IEEE, 2023: 1-8.[[pdf]("../files/DEPHN.pdf")][[pages]("https://ieeexplore.ieee.org/abstract/document/10191469")]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
