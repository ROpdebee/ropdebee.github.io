---
title: "Control and Data Flow in Security Smell Detection for Infrastructure as Code: Is It Worth the Effort?"
collection: publications
permalink: /publication/2023-msr-ansible
date: 2023-05-16
venue: Proceedings of the 20th International Conference on Mining Software Repositories (MSR'23)
venue_abbrev: MSR'23
preprinturl: 'https://soft.vub.ac.be/Publications/2023/vub-tr-soft-23-09.pdf'
citation: 'Opdebeeck, R., Zerouali, A., & De Roover, C. (2023). <i>Control and Data Flow in Security Smell Detection for Infrastructure as Code: Is It Worth the Effort?</i> In Proceedings of the 20th International Conference on Mining Software Repositories (MSR 2023).'
doi: 10.1109/MSR59073.2023.00079
related_talks:
    - name: 'Control and Data Flow in Security Smell Detection for Infrastructure as Code: Is It Worth the Effort?'
      slug: '2023-msr-ansible'
---
Infrastructure as Code is the practice of developing
and maintaining computing infrastructure through executable
source code. Unfortunately, IaC has also brought about new
cyber attack vectors. Prior work has therefore proposed static
analyses that detect security smells in Infrastructure as Code
files. However, they have so far remained at a shallow level,
disregarding the control and data flow of the scripts under
analysis, and may lack awareness of specific syntactic constructs.
These limitations inhibit the quality of their results. To address
these limitations, in this paper, we present GASEL, a novel
security smell detector for the Ansible IaC language. It uses
graph queries on program dependence graphs to detect 7 security
smells. Our evaluation on an oracle of 243 real-world security
smells and comparison against two state-of-the-art security smell
detectors shows that awareness of syntax, control flow, and data
flow enables our approach to substantially improve both precision
and recall. We further question whether the additional effort
required to develop and run such an approach is justified in
practice. To this end, we investigate the prevalence of indirection
through control and data flow in security smells across more than
15 000 Ansible scripts. We find that over 55% of security smells
contain data-flow indirection, and over 32% require a whole-project analysis to detect. These findings motivate the need for
deeper static analysis tools to detect security vulnerabilities in
IaC.
