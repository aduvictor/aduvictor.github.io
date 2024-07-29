---
title: "Miscellaneous Projects"
layout: collection
permalink: /projects/
collection: projects
entries_layout: grid
author_profile: true
sort_by: date
sort_order: reverse
classes: wide
---

# Miscellaneous Projects

Welcome to my projects portfolio! Here you will find a collection of all projects I have undertaken, ranging from professional endeavors to fun side projects. Each project represents a unique journey of learning, creativity, and problem-solving.

---

## Professional Projects

These projects showcase my professional experience and skills. They highlight my ability to deliver high-quality work in various domains.

### Featured Projects
{% assign featured_projects = site.projects | where: "category", "professional" %}
{% for project in featured_projects %}
  <div class="project">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <p>{{ project.excerpt }}</p>
    <p><a href="{{ project.url }}" class="btn">Read More</a></p>
  </div>
{% endfor %}

---

## Side Projects

In my spare time, I love to work on projects that pique my interest and allow me to explore new technologies and concepts.

### Fun and Learning
{% assign side_projects = site.projects | where: "category", "side" %}
{% for project in side_projects %}
  <div class="project">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <p>{{ project.excerpt }}</p>
    <p><a href="{{ project.url }}" class="btn">Read More</a></p>
  </div>
{% endfor %}

---

## All Projects

Browse through all the projects I have worked on. Click on any project to learn more about it.

{% for project in site.projects %}
  <div class="project">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <p>{{ project.excerpt }}</p>
    <p><a href="{{ project.url }}" class="btn">Read More</a></p>
  </div>
{% endfor %}

---

*Thank you for visiting my projects portfolio! Feel free to reach out if you have any questions or would like to collaborate on a project.*

