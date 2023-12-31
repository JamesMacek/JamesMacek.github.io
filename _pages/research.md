---
permalink: /research/
title: "Research"
author_profile: true
---

{% include base_path %}
<br><br/>

<h2> Works in progress </h2>

{% for post in site.worksinprogress reversed %}
  {% include archive-single.html %}
{% endfor %}



