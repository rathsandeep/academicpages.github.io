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

 <ul>{% for post in site.publications %}
    {% include archive.html %}
  {% endfor %}</ul>


## Journal Articles Under Review

 <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


## Other Articles

