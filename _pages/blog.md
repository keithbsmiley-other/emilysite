---
layout: page
title: Blog
skip: true
---

<div class="container">
  <div class="row">
    {% if site.posts.size > 0 %}
      {% for post in paginator.posts %}
        {% include article-content.html %}
      {% endfor %}
    {% endif %}
  </div>
</div>
{% include pagination.html %}
