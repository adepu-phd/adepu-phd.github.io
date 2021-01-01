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

My research efforts have led to high impact research outputs such as patents (x3, 1 pending), research publications (25+, 3x best paper awards, 900+ Citations), training deliveries (10+ to government agencies), workshops (4+) and teachings (100+ advanced students, Best Teaching Awards)

* Patents: [Distributed attack detection in ICS](https://patents.google.com/patent/US20200311283A1/en), [Method of detecting cyber attacks](https://patents.google.com/patent/US20200162482A1/en) and [Defense system and method against cyber-physical attacks](https://patents.google.com/patent/US20190253440A1/en).