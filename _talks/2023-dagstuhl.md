---
title: "Transposing Static Analyses from Application to Infrastructure Code: the Curious Case of Ansible"
collection: talks
permalink: /talk/2023-dagstuhl
date: 2023-02-23
venue: Dagstuhl Seminar 23082 "Resilient Software Configuration and Infrastructure Code Analysis"
type: Presentation
location: Dagstuhl, Germany
---
In this talk, we present our journey towards and our experiences in transposing static analyses from application to infrastructure code.

We realised the need to analyse infrastructure code while designing the Chaokka automated tester. Chaokka injects cloud-specific faults during the execution of a test suite to assess the resilience of a cloud-native application against these faults. The approach uses delta debugging to speed up the exploration of the corresponding fault space, which we expect to benefit further from architectural insights extracted from the supporting infrastructure code (e.g., how many replicas the application maintains of each service, …).

The second part of the talk focuses on analyses for infrastructure code in general, and Ansible in particular. To this end, we present two static representations of Ansible code. First, we describe a structural model, akin to an AST, and its applications in empirical research on Semantic Versioning in the Ansible Galaxy ecosystem. Second, we present a program dependence graph representation that captures the control and data flow of an Ansible script. We describe the challenges faced when building such graphs, caused by unconventional and undocumented Ansible semantics. Finally, we describe two applications of Ansible program dependence graphs, namely the detection of variable-related smells, and a graph pattern mining approach to defect detection.
