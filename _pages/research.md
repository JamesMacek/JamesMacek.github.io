---
permalink: /research/
title: "Research"
author_profile: true
---

{% include base_path %}
<br/>

<h2> Working papers </h2>
<br/>

{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
<br style="line-height: 0.25;"/>
{% endfor %}

<h2> Works in progress </h2>
<br/>

{% for post in site.worksinprogress reversed %}
  {% include archive-single.html %}
<br style="line-height: 0.25;"/>
{% endfor %}



