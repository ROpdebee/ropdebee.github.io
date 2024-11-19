---
title: "Mining for Graph-Based Library Usage Patterns in COBOL Systems"
collection: publications
permalink: /publication/2021-saner
date: 2021-03-09
venue: Proceedings of the 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER'21)
venue_abbrev: SANER'21
pdf_url: 'https://soft.vub.ac.be/Publications/2021/vub-tr-soft-21-01.pdf'
pdf_type: Pre-print
doi: 10.1109/SANER50967.2021.00072
citation: 'Opdebeeck, R., Fabry, J., Molderez, T. C., De Bleser, J., & De Roover, C. (2021). <i>Mining for Graph-Based Library Usage Patterns in COBOL Systems.</i> In Proceedings of the 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (pp. 595-599). IEEE.'
related_talks:
    - name: 'Mining for Graph-Based Library Usage Patterns in COBOL Systems'
      slug: '2021-saner'
---
When migrating legacy systems to more contemporary platforms, it is not always feasible to migrate their external library dependencies as well. A workaround can be to partially reimplement the library dependencies on the new platform, limiting oneself to the features that are used by the migrated system. For contemporary programming languages, several approaches to mining for library usage patterns have been proposed. For legacy programming languages, in contrast, such tools are lacking. This encumbers establishing what parts of a library need to be rewritten during a migration project, especially when considering large-scale systems.
In this industry track paper, we present an approach to mining library usage patterns in COBOL code. We describe a library usage extractor for COBOL, which produces graphs that capture the control and data flow involved in library calls. The extractor supports legacy control flow features, such as GO TO. We use these graphs as input to two state-of-the-art frequent subgraph mining algorithms, and report on the scalability of their use for mining common library usage patterns in two industrial COBOL systems. The mined library usage patterns can help assess and subsequently steer the migration effort.
