---
layout: page
title: Weekly Updates
permalink: /blog/
---

# Weekly Updates

This is where I track my weekly progress and reflections.  
Each post includes what I worked on, what I learned, and where I’m working on next.

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
