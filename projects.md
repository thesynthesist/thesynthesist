---
layout: default
title: Projects
---

<section>
  <h1>Projects</h1>
  <ul>
    {% for project in site.projects %}
      <li>
        <strong>{{ project.title }}</strong> — {{ project.description }}
        {% if project.link %}
        [<a href="{{ project.link }}">Listen</a>]
        {% endif %}
      </li>
    {% endfor %}
  </ul>
</section>
