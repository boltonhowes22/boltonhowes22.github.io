---
layout: archive
title: "Templates"
permalink: /templates/
author_profile: true
---

{% include base_path %}


{% for post in site.templates reversed %}
  {% include archive-single.html %}
{% endfor %}
