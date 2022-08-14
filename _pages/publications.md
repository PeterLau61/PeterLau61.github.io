---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## [Boosting the Transferability of Adversarial Attacks with Reverse Adversarial Perturbation](https://openreview.net/forum?id=i7FNvHnPvPc)

Zeyu Qin<sup>\*</sup>, Yanbo Fan<sup>\*</sup>, **Yi Liu**<sup>\*</sup>, Yong Zhang, Jue Wang, Baoyuan Wu<sup>^</sup>. Submitted to *NeurIPS'22*.

<sup>\*</sup> Equal Contributoin. <sup>^</sup> Corresponding Author.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
