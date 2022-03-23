---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

An up-to-date list of my publications can be found on NASA ADS at [this link](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0001-6180-8482&sort=date%20desc%2C%20bibcode%20desc&p_=0). 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
