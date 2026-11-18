---
layout: profile
title: Funded research projects
permalink: /projects/
redirect_from:
  - /portfolio/
---

Collaborative European and national funded projects in which I have participated. Each page separates the project's aims from my individual contribution; detailed roles are included only where supported by the supplied material.

<div class="project-grid">{% assign projects = site.portfolio | where: 'kind', 'funded-project' | sort: 'order' %}{% for project in projects %}{% include project-card.html project=project %}{% endfor %}</div>
