---
layout: page
permalink: /repositories/
title: repositories
description: A collection of my GitHub repositories.
nav: true
nav_order: 7
---

{% if site.data.repositories.github_repos %}

## Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>

{% endif %}

For more, check out my [GitHub page](https://github.com/jinmiyoon).
