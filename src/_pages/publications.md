---
layout: single
permalink: publications
author_profile: true
years: [2019,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008]
---

{% for y in page.years %}
  {% bibliography -q @*[year={{y}}]* %}
{% endfor %}
