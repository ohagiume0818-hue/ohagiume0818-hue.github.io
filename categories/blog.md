---
layout: page
title: "ブログ運営記"
permalink: /categories/blog/
---

「Gitって何?」というところから、ブログを立ち上げ・公開・運営していく過程の記録です。

<ul class="post-list">
{% for post in site.categories['ブログ運営記'] %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h3>
  </li>
{% endfor %}
</ul>
