---
title: "The Pitfalls of Ansible’s Variable and Template Expression Semantics"
collection: publications
permalink: /publication/2021-conflang
published_prefix: 'Unpublished presentation abstract'
date: 2021-10-18
venue: 1st Workshop on Configuration Languages (CONFLANG)
venue_abbrev: CONFLANG
paperurl: 'https://researchportal.vub.be/files/75908280/conflang21.pdf'
citation: 'Opdebeeck, R., & De Roover, C. (2021). <i>The Pitfalls of Ansible’s Variable and Template Expression Semantics.</i> Abstract from 1st Workshop on Configuration Languages, Chicago, United States.'
related_talks:
    - name: The Pitfalls of Ansible’s Variable and Template Expression Semantics (full)
      slug: 2021-conflang-full
    - name: The Pitfalls of Ansible’s Variable and Template Expression Semantics (lightning)
      slug: 2021-conflang-short
---

Ansible is a widely-used Infrastructure-as-Code (IaC) language for managing the configuration of machines in a digital infrastructure. The reliability of configuration definition files, which Ansible calls “playbooks”, is of the upmost importance. However, Ansible employs semantics unlike those found in traditional programming languages, the unexpected behaviour of which could surprise developers. Next to forming a steep learning curve for newcomers, this semantics also hinders both manual and mechanical verification. In this presentation, we will show a number of potential pitfalls caused by a combination of unconventional semantic properties of Ansible variables and template expressions.
The purpose of this talk is three-fold:
1) To spread awareness of the unconventional semantics of Ansible and possible pitfalls to practitioners.
2) To entice tool builders to work on code analysers and bug detectors related to these pitfalls.
3) To stimulate language designers to address these pitfalls with safer alternatives.
