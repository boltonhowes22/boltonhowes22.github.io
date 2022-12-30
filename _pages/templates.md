---
layout: archive
title: "Templates"
permalink: /templates/
author_profile: true
---
I realized that I was spending a lot of time battling formatting (for CVs, presentation slides, cover letters, etc), so I decided to put all my templates in one place because I figured other people might be running in to the same issues and the templates could save them time. If you have recommendations for improving them, please let me know!


Here they are: 
 - [LaTeX template for a CV](https://boltonhowes22.github.io/files/cv.tex)
 - [Cover letter for manuscript submissions](https://boltonhowes22.github.io/files/cover-letter-template.zip)
 - coming soon: cover letter for official communcations, inDesign presentation slides, generic latex paper writing template.


{% include base_path %}


{% for post in site.templates %}
  {% include archive-single.html %}
{% endfor %}
