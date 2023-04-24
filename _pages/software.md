---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

You'll find most of our software on the [gravellab github page](https://github.com/gravelLab) and [Simon Gravel's github](https://github.com/sgravel). 


{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.softwarename %}
    {% include archive-single-software.html %}
  {% endif %}
{% endfor %}
