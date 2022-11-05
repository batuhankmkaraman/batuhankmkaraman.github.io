---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
For more details, see my Google Scholar profile.
{% if author.googlescholar %}
  For more details, see my <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
