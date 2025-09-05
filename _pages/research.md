---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<iframe src="https://drive.google.com/file/d/1HQcKWTPr7m3WwAbY7AJNQDAFRlahElbj/preview" width="640" height="480"></iframe>

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
