---
title: 项目介绍 Projects
nav:
  order: 2
  tooltip: 正在开展或已完成的重大项目
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

项目总览介绍

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
