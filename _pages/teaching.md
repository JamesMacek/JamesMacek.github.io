---
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}
<br/>

<h2> Courses </h2>
<br/>

{% for post in site.teaching reversed %}
  <div class="teaching-card">
    {% include archive-single.html %}
  </div>
<br style="line-height: 0.25;"/>
{% endfor %}
