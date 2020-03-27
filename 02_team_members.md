---
layout: default
title: Team Members
permalink: /team_members/
---

<h1>Team Members</h1>

{% for team_member in site.team_members %}

<h2>
  <a href="{{ team_member.url }}">
    {{ team_member.name }} - {{ team_member.position}}
  </a>
</h2>
{% endfor %}
