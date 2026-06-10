---
layout: page
title: "原点・考え方"
permalink: /categories/genten/
---

「満員電車に乗らない生き方」を目指す理由など、挑戦の原点や考え方についての記事です。

<ul class="post-list">
{% for post in site.categories['原点・考え方'] %}
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
