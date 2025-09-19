---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<iframe src="https://drive.google.com/file/d/1HQcKWTPr7m3WwAbY7AJNQDAFRlahElbj/preview"width="640" height="480" allow="autoplay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"></iframe>

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
