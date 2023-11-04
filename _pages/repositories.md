---
layout: page
permalink: /software/
title: software
description: Initially, I developed scientific computing software. Recently, I've become interested in inference on the edge for LLM. I code mainly in Python, C and C++.
nav: true
nav_order: 3
---

## main projects

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
