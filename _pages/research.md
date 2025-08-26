---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<object data="files/Information Framing Effects on Individual Climate Urgency.pdf" width="1000" height="1000" type='application/pdf'></object>

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
