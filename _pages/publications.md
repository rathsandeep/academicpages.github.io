---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}



## Peer Reviewed Journal Articles

 <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv-expanded.html %}
  {% endfor %}</ul>


## Journal Articles Under Review

 <ul>{% for post in site.reviewpubs reversed %}
    {% include archive-single-cv-expanded.html %}
  {% endfor %}</ul>


## Other Articles

