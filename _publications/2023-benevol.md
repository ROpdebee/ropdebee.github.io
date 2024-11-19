---
title: "Behaviour-aware Security Smell Detection for Infrastructure as Code"
collection: publications
permalink: /publication/2023-benevol
published_prefix: 'Unpublished presentation abstract'
date: 2023-11-27
venue: 22nd Belgium-Netherlands Software Evolution Workshop (BENEVOL'23)
venue_abbrev: BENEVOL'23
pdf_url: 'https://researchportal.vub.be/files/106024786/main.pdf'
citation: 'Opdebeeck, R., Zerouali, A. & De Roover, C. (2023). <i>Behaviour-aware Security Smell Detection for Infrastructure as Code.</i> Abstract from 22nd Belgium-Netherlands Software Evolution Workshop, Nijmegen, Netherlands.'
related_talks:
    - name: Behaviour-aware Security Smell Detection for Infrastructure as Code
      slug: 2023-benevol
---
Infrastructure as Code (IaC) is a vital part of modern DevOps workflows, and the security of deployed infrastructures is of the upmost importance. In this presentation, we will highlight the importance of taking into account IaC script behaviour when detecting security smells. Specifically, we present gasel, a security smell detector based on program dependence graphs, which takes into account the control and data flow of Ansible IaC scripts. gasel supports 7 distinct security weaknesses, such as hardcoded passwords and missing integrity checks. Using an oracle of 243 real-world weaknesses, we show that gasel outperforms the state-of-the-art detectors. Moreover, we perform an empirical study on more than 15.000 Ansible scripts to show that the inclusion of control and data flow information is vital to detect security smells in real-world code.
