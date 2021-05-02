---
title: Blog
icon: ✍️
---

*Hier schreibe ich über Dinge, die mich interessieren, die ich teilen möchte, die ich gelernt habe, die ich schon immer einmal sagen wollte oder die mir schlicht gerade durch den Kopf gegangen sind.*

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} ({{ post.date | date: "%d.%m.%Y" }})</a>
    </li>
  {% endfor %}
</ul>
