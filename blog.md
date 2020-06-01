---
layout: page
path: blog
title: Blog
---
  
<div class="card-deck">

  {% for post in site.posts %}
    {% include blog/blog-card.html %}
  {% endfor %}
  
</div>