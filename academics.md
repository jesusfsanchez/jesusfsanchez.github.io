---
layout: default
title: "Home"
---
{%- assign pages = paginator.pageacademics}
{% for page in pages %}
  <article>
    {{ page.excerpt }}
    <div class="more"><a href="{{ page.url | relative_url }}">read more</a></div>
  </article>
{% endfor %}
