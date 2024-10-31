---
layout: archive
title: "Blog Posts"
permalink: /blogs/
author_profile: true
---


  I have authored several blogs across different domains, including [tornadovm.org](https://www.tornadovm.org/blog), [foojay.io](https://foojay.io/today/author/thanos-stratikopoulos/), and EU-funded research projects [ELEGANT](https://www.elegant-h2020.eu/), [ENCRYPT](https://encrypt-project.eu/) & [TANGO](https://tango-project.eu/).


{% include base_path %}

{% for post in site.blogs reversed %}
  {% include archive-single.html %}
{% endfor %}

