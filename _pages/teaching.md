---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

Beyond research, I have been a physics laboratory teaching assistant for over two years where I led labs, graded student work, and held office hours. I also worked on the transition of the labs to online instruction during the COVID-19 pandemic by restructuring lab resources and creating new grading guidelines. Interacting with students gave me an opportunity to understand the challenges that limit student success, which then informed my service goals. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
