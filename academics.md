---
layout: default
title: "Home"
---

  <article>
    {% include usc.md %}
    {{ usc.excerpt }}
    <div class="more"><a href="{{ usc.url | relative_url }}">read more</a></div>
  </article>

  <article>
    {% include csun.md %}
    {{ csun.excerpt }}
    <div class="more"><a href="{{ csun.url | relative_url }}">read more</a></div>
  </article>
