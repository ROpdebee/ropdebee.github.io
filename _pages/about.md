---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a post-doctoral researcher at the [Software Languages Lab](https://soft.vub.ac.be/soft/) of the [Vrije Universiteit Brussel](https://www.vub.be/).
My research mainly revolves around defect detection for Infrastructure as Code, with a focus on the Ansible language.
My research interests include software quality and code smells, pattern mining in source code, anomaly detection, library/API usages, and mining software repositories.

In October 2024, I obtained a Ph.D. in Computer Sciences with a dissertation entitled “Static Analysis for Quality Assurance of Ansible Infrastructure-as-Code Artefacts” at Vrije Universiteit Brussel under the supervision of [Prof. Dr. Coen De Roover](https://soft.vub.ac.be/~cderoove/), available for download [here](/files/ropdebee-phdthesis.pdf).
In 2019, I obtained my MSc in Applied Sciences and Engineering: Computer Sciences at Vrije Universiteit Brussel with a MSc thesis titled “Exploring Static Inter-Procedural API Misuse Detection Using Graph Inlining”, available for download [here](/files/vub-soft-ms-19-03-ropdebee.pdf).
In 2017, I obtained my BSc in Computer Sciences at Vrije Universiteit Brussel with a BSc thesis titled “Towards Template-Driven Source Code Transformations in C++”, available for download [here](/files/ropdebee-bachelorthesis.pdf).

## Recent publications

<ul>
{% assign recent_pubs = site.publications | reverse | slice: 0, 3 %}
{% for post in recent_pubs %}
  <li>{{ post.date | date: "%B %d, %Y" }}: <a href="{{ post.permalink }}">{{ post.title }} ({{ post.venue_abbrev | default: post.type }})</a></li>
{% endfor %}
</ul>

## Recent/upcoming talks and presentations

<ul>
{% assign recent_talks = site.talks | reverse | slice: 0, 3 %}
{% for post in recent_talks %}
  <li>{{ post.date | date: "%B %d, %Y" }}: <a href="{{ post.permalink }}">{{ post.title }} ({{ post.location }})</a></li>
{% endfor %}
</ul>
