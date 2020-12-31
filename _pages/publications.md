---
layout: archive
title: "Publications and Impact"
permalink: /publications/
author_profile: true
---
You can find all of my articles on [Google Scholar](https://scholar.google.com/citations?user=sSAQkAgAAAAJ&hl=en&oi=ao).
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Impact:
======