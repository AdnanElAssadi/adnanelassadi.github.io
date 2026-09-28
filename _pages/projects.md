---
layout: page
permalink: /projects/
title: projects
description:
nav: true
nav_order: 3
---

I'm a core maintainer of [MTEB](https://github.com/embeddings-benchmark/mteb), which has 25M+ downloads.

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
