---
layout: default
title: Welcome to the Cat Forum
---

# {{ page.title }}

{% for post in site.posts reversed %}
  [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

<small style="position:fixed;bottom:0;left:50%;transform:translate(-50%);">
  [&copy; bmordan](https://github.com/bmordan)
</small>
