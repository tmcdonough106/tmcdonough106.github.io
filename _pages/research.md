---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<iframe src="https://docs.google.com/document/d/e/2PACX-1vRlWJGEw19S_XmoGn1DUos_TX0IehsAMzkcWq1oIFAyVqTt9dkNAAmfi_57PU25SDbs0_jYEyw7LqQh/pub?embedded=true"></iframe>

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
