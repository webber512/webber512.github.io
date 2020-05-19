---
layout: page
path: portfolio
title: Portfolio
---

<div class="card-deck">
{% for project in site.projects %}
  <div class="card">
    <img class="card-img-top" src="assets/img/{{project.photo}}" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title"><a href="{{ project.url }}">{{ project.name }}</a></h5>
      <p class="card-text">{{ project.description}}</p>
      <p class="card-text"><small class="text-muted">{{ project.date | date: '%B %d, %Y'}}</small></p>
    </div>
  </div>
{% endfor %}
</div>
