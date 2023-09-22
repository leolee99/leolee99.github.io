---
layout: page
permalink: /Github/
title: Github
description: The stats of my <a href='https://github.com/leolee99' target="_blank">Github</a>.
nav: false
nav_order: 3
---

## GitHub users

![Leo.Lee's GitHub stats](https://github-readme-stats-one-bice.vercel.app/api?username=leolee99&show_icons=true&include_all_commits=true&count_private=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR)


## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
