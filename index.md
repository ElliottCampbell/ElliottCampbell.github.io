---
layout: default
title: Your Name
description: Add a short description of yourself or your site.
---

# Welcome to My GitHub Pages Site

Hello, I'm [Your Name](https://github.com/yourusername). This is my personal GitHub Pages site.

## About Me

Add a brief introduction or description of yourself here.

## Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
  {{ post.excerpt }}
{% endfor %}

## Projects

List your projects or highlight some of your repositories.

1. [Project 1](https://github.com/yourusername/project1): Brief description.
2. [Project 2](https://github.com/yourusername/project2): Brief description.
3. ...

## Contact Information

- GitHub: [github.com/yourusername](https://github.com/yourusername)
- Twitter: [@yourtwitterhandle](https://twitter.com/yourtwitterhandle)
- Email: your.email@example.com

