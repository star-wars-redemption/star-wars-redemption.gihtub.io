---
layout: page
title: Scénarios
---

Avec le manuel du joueur, voici quelques scénarios écrit spécialement pour SWR :

{% for post in site.tags.scenario %}
![Uhumele]({{ site.img_dir | append: post.image | absolute_url }}){: .right .thumbnail}

## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

---
{% endfor %}