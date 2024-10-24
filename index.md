---
layout: home
title: some title
subtitle: no subtitle here
twitter: lowcraft.org
---

<p>https://twitter.com/{{ page.twitter }}</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>