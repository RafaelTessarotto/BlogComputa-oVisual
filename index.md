---
layout: page
title: "Início"
---

Aqui estão as minhas anotações e trabalhos da aula de Computação Visual.

### Meus Posts:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}
