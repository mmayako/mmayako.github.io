---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Here is a collection of scholarly articles I have published. They are organized in reverse chronogical order. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
