---
lesson- example: "https://carpentries.github.io/lesson-example/" 
layout: default
title: "Learning how to build wensite with Jekyll"
---


## Description
{{ site.description }}

{{% assign lead = site.team_memebers | where: "role", "project lead" | first %}
The rpoejct is led by {{ lead.name}}.
[See our full team](/about#team)

More details about the project are available from the [About page](about.md)

See more [example]( {{ page.lessson-example }})






