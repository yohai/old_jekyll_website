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
    <div class="row">
      <div class="col-sm">
        <img src="/assets/img/group_spring.jpg" class="img-fluid">
      </div>
    </div>
    <div class="grid">
      {% for member in site.data.team_members %}
        {% include team_member.html %}
      {% endfor %}
    </div>
    <div class="row">
      <div class="col-sm">
        <img src="/assets/img/group_icecream.png" class="img-fluid">
      </div>
    </div>
</div>