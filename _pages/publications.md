---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

In preparation
------
* G. Moreland, *Higher codimension nef and effective cycles on the Hilbert scheme of 3 points in projective 3-space* Pre-print available [here].(https://arxiv.org/abs/2403.08918)
* G. Moreland, *Postulation of a union of one double plane and many lines.* In preparation.

Accepted
------
* M. Brandt, J. Bruce, M. Chan, M. Melo, G. Moreland, C. Wolfe, *On the top-weight rational cohomology of $A_g$.* Geometry & Topology, to appear.
[arXiv:2012.02892](https://arxiv.org/abs/2012.02892)

* J. DeWitt, K. Ford, E. Goldstein, S.J. Miller, G. Moreland, E. Palsson, S. Senger, *Dimensional lower bounds for Falconer type incidence and point configuration theorems.* JAMA (2019)
[arXiv:1612.00539](https://arxiv.org/abs/1612.00539)

* S. Gastineau and G. Moreland, *A binomial Laurent phenomenon algebra associated to the complete graph.* J. Algebr Comb (2017)
[arXiv:1506.01416](https://arxiv.org/abs/1506.01416)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
