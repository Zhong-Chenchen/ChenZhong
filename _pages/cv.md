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
* Wuhan University

Research Interests
======
* Efficient multimodal large language models
* Visual token pruning and compression
* Vision-language understanding and reasoning

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
