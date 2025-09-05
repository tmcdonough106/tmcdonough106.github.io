---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<div style="position: relative; width: 100%; padding-top: 56.25%; height: 0;">
    <iframe src="https://docs.google.com/document/d/1sBtoLOOnQNQ-C1q83HMoc2XCHqjZLfclSSZV5ZhotZo/edit?usp=drive_link" width="640" height="480" allow="autoplay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"></iframe>
</div>

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
