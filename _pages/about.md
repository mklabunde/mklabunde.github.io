---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD student at the University of Passau advised by Professor Florian Lemmerich.
My work currently focuses on studying similarity of neural networks.


# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-minimal.html %}
{% endfor %}

<!-- # Teaching -->

<!-- {% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %} -->