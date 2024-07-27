---
permalink: /projects/
layout: splash
classes: wide

projects:
  - title: "Inertia Frame of an Object Using Stereo Camera "
    description: "The aim of this project is to crete a system the utilizes multiple "
    link: "https://linktoyourprojectone.com"
  - title: "Project Two"
    description: "This is a brief description of Project Two."
    link: "https://linktoyourprojecttwo.com"
  - title: "Project Three"
    description: "This is a brief description of Project Three."
    link: "https://linktoyourprojectthree.com"
---

<h1>Projects</h1>
<div class="projects-list">
  {% for project in page.projects %}
    <div class="project">
      <h2>{{ project.title }}</h2>
      <p>{{ project.description }}</p>
      <a href="{{ project.link }}" target="_blank">Learn More</a>
    </div>
  {% endfor %}
</div>
