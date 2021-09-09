---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=uAJkthMAAAAJ&hl=en) and [ACM Digital Library profile](https://dl.acm.org/profile/99659558585).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
