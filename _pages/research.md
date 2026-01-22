---
permalink: /research/
title: "Research"
author_profile: true
---

{% include base_path %}
<br/>

<h2> Publications </h2>
<br/>

{% for post in site.publications reversed %}
  <div class="research-card">
    {% include archive-single.html %}
  </div>
<br style="line-height: 0.25;"/>
{% endfor %}

<h2> Working papers </h2>
<br/>

{% for post in site.workingpapers reversed %}
  <div class="research-card">
    {% include archive-single.html %}
  </div>
<br style="line-height: 0.25;"/>
{% endfor %}

<h2> Selected works in progress </h2>
<br/>

{% for post in site.worksinprogress reversed %}
  {% include archive-single.html %}
<br style="line-height: 0.25;"/>
{% endfor %}



