---
layout: default
title: "Home"
---

{% include usc.md %}
  <article>
    {{ usc.excerpt }}
    <div class="more"><a href="{{ usc.url | relative_url }}">read more</a></div>
  </article>

{% include csun.md %}
  <article>
    {{ csun.excerpt }}
    <div class="more"><a href="{{ csun.url | relative_url }}">read more</a></div>
  </article>
