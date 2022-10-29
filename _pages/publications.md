---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

In preparation
------
1. Test
1. Test
Accepted
------
1. M. Brandt, J. Bruce, M. Chan, M. Melo, G. Moreland, C. Wolfe, *On the top-weight rational cohomology of $A_g$.* Geometry & Topology, to appear.
1. J. DeWitt, K. Ford, E. Goldstein, S.J. Miller, G. Moreland, E. Palsson, S. Senger, *Dimensional lower bounds for Falconer type incidence and point configuration theorems.* JAMA (2019)
1. S. Gastineau and G. Moreland, *A binomial Laurent phenomenon algebra associated to the complete graph.* J. Algebr Comb (2017)
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
