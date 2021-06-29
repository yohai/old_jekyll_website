---
layout: page
title: team
permalink: /group/
description: 
nav: true
display_categories: []
horizontal: false
---
<div class="projects container">
    <div class="grid">
      {% for member in site.data.team_members %}
        {% include team_member.html %}
      {% endfor %}
    </div>
</div>

