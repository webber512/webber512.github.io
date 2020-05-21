---
layout: page
path: projects
url: projects
title: Projects
---

<div class="card-deck">
{% for project in site.projects %}
 <a href="{{ project.url }}">
  <div class="card rounded mb-3" style="min-width: 18rem; max-width: 24rem;">
    <img class="card-img-top" src="../assets/img/{{project.photo}}" alt="Card image cap">
    <div class="card-body">
      <h4 class="card-title"><a href="{{ project.url }}">{{ project.name }}</a></h4>
      <p class="card-text">{{ project.description}}</p>
      <p class="card-text"><small class="text-muted">{{ project.date | date: '%B %d, %Y'}}</small></p>
    </div>
  </div>
  </a>
{% endfor %}
</div>
