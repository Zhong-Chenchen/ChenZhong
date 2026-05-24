---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. student, State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing (LIESMARS), Wuhan University, 2025 - now
* B.S., School of Electronic Information, Wuhan University, 2025

Research Interests
======
* Vision-language models
* Large language models
* Remote sensing

Skills
======
* Python, PyTorch
* Multimodal model evaluation
* Research software development

Publications
======
{% if site.publications.size == 0 %}
Publication list coming soon.
{% else %}
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% endif %}
