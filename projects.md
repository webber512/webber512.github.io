---
layout: page
path: projects
url: projects
title: Projects
---
Below are some of the projects that I have worked on in the last few years. Most projects are technical in nature, focusing on Java with a database backend, however, I have also completed an introductory research paper, and a technical manual, all of which can be found below. If you would like more information on any of these projects, contact me, I would love to share more details!
<div class="card-deck">
{% for project in site.projects %}
 <a href="{{ project.url }}">
  <div class="card rounded mb-3" style="min-width: 20rem; max-width: 34rem;">
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


