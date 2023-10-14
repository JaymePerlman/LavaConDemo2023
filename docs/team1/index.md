---
layout: page
title: Toc Testing
---

## TOC

{% for doc in site.team1 %}
- [{{ doc.data.title }}]({{ doc.url }})
{% endfor %}

## Additional resources

- For a **fantastic** how-to on building a repo designed from the ground up to be open-sourced AND enabled for OpenAPI, see the [OSS Example Template Repo](https://github.com/therzka/OSS-Example-Repo)
