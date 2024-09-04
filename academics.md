---
layout: default
title: "Home"
---

{% for page in pageacademics %}
  <article>
    {{ page.excerpt }}
    <div class="more"><a href="{{ page.url | relative_url }}">read more</a></div>
  </article>
{% endfor %}
