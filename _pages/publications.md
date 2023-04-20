---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find most of the lab articles on <u><a href="https://scholar.google.com/citations?user=0wQ8O80AAAAJ&hl=fr"> Simon Gravel's Google Scholar profile</a>.</u>

Some selected publications:

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
