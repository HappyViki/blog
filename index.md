---
layout: default
title: Veronicodes Blog
---

# Welcome to my blog :)

I'm growing a lot as a software developer, and I thought: what better way to document what I’m learning than through a blog!?

Quick recap of who I am: My preferred language is JavaScript. I started out as a full-stack WordPress developer, then moved into React development, and now I do a mix of both. I’m currently niching down to help .NET developers with frontend work. I built an MVC app that accepts Stripe payments to showcase my C# abilities.

---

## Recent Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span>— {{ post.date | date: "%b %d, %Y" }}</span>
  </li>
{% endfor %}
</ul>
