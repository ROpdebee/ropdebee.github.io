---
title: "Performance Testing in Open-Source Web Projects: Adoption, Maintenance, and a Change Taxonomy"
collection: publications
permalink: /publication/2025-icsme-sergio
date: 2025-05-01
venue: Proceedings of the 41st IEEE International Conference on Software Maintenance and Evolution (ICSME'25)
venue_abbrev: ICSME'25
pdf_url: 'https://soft.vub.ac.be/Publications/2025/vub-tr-soft-25-05.pdf'
pdf_type: Pre-print
citation: "Di Meglio, S., Starace, L. L. L., Pontillo, V., Opdebeeck, R., De Roover, C., & Di Martino, S. (2025). <i>Performance Testing in Open-Source Web Projects: Adoption, Maintenance, and a Change Taxonomy</i> In Proceedings of the 41st IEEE International Conference on Software Maintenance and Evolution (ICSME '25) [Accepted]."
---
Performance testing is crucial to ensuring that web applications meet user expectations under varying workloads. Activities such as stress, load, and smoke testing are designed to simulate different kinds of simultaneous user interactions and assess system behavior. Despite its recognized importance in quality assurance of large-scale web-based systems, witnessed by numerous studies proposing solutions to support these activities, the real-world adoption and evolutionary dynamics of performance tests have received limited attention in the literature. To fill this gap, we analyzed 77 open-source web projects using APACHE JMETER and LOCUST. Our study investigates how performance tasks are performed (adoption time, load design, types of tasks), the characteristics of projects that adopt them, and their long-term maintenance. Our findings reveal that performance tests in open-source projects are simple, with a focus on single-user behaviors and minimal requests, and most tests have low concurrency. Load tests are the most common, followed by smoke and stress tests. Projects with performance tests tend to be larger and more actively maintained. However, tests are mostly long-lived but rarely updated, suggesting potential risks to their relevance and coverage over time. Finally, by creating a taxonomy of performance test changes, we observe recurring patterns of modifications, including workload adjustments, network request changes, and updates to system monitoring.
