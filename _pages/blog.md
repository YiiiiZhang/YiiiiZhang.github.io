---
layout: page
title: "Blog"
permalink: /blog/
---

Occasional notes on research, tools, and things I'm learning.

<ul class="post-list" style="list-style:none; padding:0;">
{% for post in site.posts %}
  <li style="padding:14px 0; border-bottom:1px solid var(--border);">
    <a href="{{ post.url | relative_url }}" style="font-weight:600; font-size:1.08rem;">{{ post.title }}</a>
    <div style="color:var(--muted); font-size:0.9rem;">{{ post.date | date: "%B %-d, %Y" }}</div>
    {% if post.excerpt %}<p style="margin:6px 0 0;">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>{% endif %}
  </li>
{% endfor %}
</ul>
