---
layout: archive
title: "Service Work"
permalink: /service/
author_profile: true
---
Beyond academics, I have been heavily involved in physics based service projects. Working with undergrads has been the highlight of my time at UD and I plan on continuing this in grad school. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.service reversed %}
  {% include archive-single.html %}
{% endfor %}

