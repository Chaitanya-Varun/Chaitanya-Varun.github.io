---
layout: modern-page
title: "News"
eyebrow: "Recent updates"
description: "A compact record of research, engineering, and academic milestones."
permalink: /news/
---

<ol class="news-page-list">
  {% for item in site.data.news %}
    <li>
      <time>{{ item.date }}</time>
      <div><h2>{{ item.summary }}</h2></div>
    </li>
  {% endfor %}
</ol>
