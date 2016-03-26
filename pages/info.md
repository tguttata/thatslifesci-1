---
layout: page
title: "About"
subheadline: "About BioBlog"
teaser: ""
permalink: "/info/"
header: no
---
**That's Life Science** is a free source of articles about many different topics within the realm of life science. It was created by an interdisciplinary collective of life science graduate students who strive to provide ready access of life science to the general public. We examine life at many levels, from looking <Inside the Body> to examining the relationship between us and <The Environment>. If you need your daily fix of animal pictures and videos, find some new favorites in <Plants & Animals>. Come with us to our labs and field sites in our <Grad School Diaries> to see what the day-to-day is like as a scientist. Join us each week as we explore the circle of life through the eyes of science!

**TEAM**
{% for author_entry in site.data.authors %}{% assign author = author_entry[1] %}
Name: {% if author.name %}{{ author.name }}{% else %}{{ site.author }}{% endif %}{% if author.siteroles %}
Role: {{ author.siteroles }}{% endif %}{% if author.uri %}
Site: {{ author.uri }}{% endif %}{% if author.twitter %}
Twitter: {{ author.twitter }}{% endif %}
{% endfor %}
