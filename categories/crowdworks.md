---
layout: page
title: "クラウドワークス挑戦記"
permalink: /categories/crowdworks/
---

クラウドワークスで月100万円を目指して、未経験から営業・案件対応に挑戦していく記録です。

<ul class="post-list">
{% for post in site.categories['クラウドワークス挑戦記'] %}
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
