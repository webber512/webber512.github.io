---
name: Coronavirus Dashboard
layout: project
url: covid-dashboard
title: Coronavirus Dashboard
date: 2020-05-28
photo: covid-dashboard.png
description: A Spring Boot application designed to provide detailed visualizations about the Coronavirus Outbreak in the United States, utilizing my COVID Data Wrapper.
---

The Coronavirus Dashboard is a spring boot application designed to provide detailed data visualizations about the Coronavirus Outbreak in the United States, utilizing data from
<a href="https://covidtracking.com/">The COVID Tracking Project</a> and my <a href="https://github.com/webber512/covid-data-library">Java COVID Data Library Wrapper</a>. Designed with Bootstrap 4.5, the Coronavirus Dashboard is designed to work on screens of all sizes, showing critical and accurate data about the spread of COVID-19 in the United States.

<div class="row">
<div class="col-md-6">
<div markdown="1">

## Current Features

- Clean design for all devices with Bootstrap 4.5
- Up-to-date views of cases, deaths, and testing resources
- Change over time information viewable via graphs for country and state level
- Maps of cases, deaths, and tests, and per-capita data
- Table comparison of all 50 states showing detailed data

## Planned Features

- Updated map information
- Mobile enhancements
- Ability to export data to different formats

</div>
</div>
<div class="col-md-6">
<div markdown="1">
<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100" src="/assets/img/covid-dashboard.png" alt="First slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="/assets/img/covid-dashboard2.png" alt="Second slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="/assets/img/covid-dashboard3.png" alt="Third slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="/assets/img/covid-dashboard4.png" alt="Fourth slide">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>
</div>
<br/>
</div>
</div>

## Contributing

If you are interested in contributing to the project, check it out on GitHub! Feel free to submit a pull request or issue to share your feedback.

<center>
{% include elements/button.html link="https://github.com/webber512/coronavirus-dashboard" text="View the Dashboard" %}
{% include elements/button.html link="https://github.com/webber512/coronavirus-dashboard" text="GitHub Repository" %}
{% include elements/button.html link="https://github.com/webber512/coronavirus-dashboard" text="Download Latest" %}
</center>
