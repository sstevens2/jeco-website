---
lesson- example: "https://carpentries.github.io/lesson-example/" 
layout: default
title: "Learning how to build wensite with Jekyll"
---


## Description
{{ site.description }}

{% assign lead = site.team_memebers | where: "role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](about#team)

More details about the project are available from the [About page](about.md)

See more [example]( {{ page.lessson-example }})

## Blog Posts

{% for post in site.posts | sort: "author" %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url )}}) by {{ post.author}}
{% endfor %}





