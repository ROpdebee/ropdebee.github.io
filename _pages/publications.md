---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my publications on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>{% if site.author.dblp %} or <a href="{{site.author.dblp}}">my dblp profile</a>{% endif %}.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
