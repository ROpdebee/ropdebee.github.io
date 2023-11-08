---
title: "Helm Charts for Kubernetes Applications: Evolution, Outdatedness and Security Risks"
collection: publications
permalink: /publication/2023-msr-helm
date: 2023-05-16
venue: Proceedings of the 20th International Conference on Mining Software Repositories (MSR'23)
venue_abbrev: MSR'23
preprinturl: 'https://soft.vub.ac.be/Publications/2023/vub-tr-soft-23-08.pdf'
citation: 'Zerouali, A., Opdebeeck, R. & De Roover, C. (2023). <i>Helm Charts for Kubernetes Applications: Evolution, Outdatedness and Security Risks</i> In Proceedings of the 20th International Conference on Mining Software Repositories (MSR 2023).'
doi: 10.1109/MSR59073.2023.00078
related_talks:
    - name: 'Helm Charts for Kubernetes Applications: Evolution, Outdatedness and Security Risks'
      slug: '2023-msr-helm'
---
Using Kubernetes for the deployment, management
and scaling of containerized applications has become a common
practice. To facilitate the installation and management of these
applications, practitioners can use the Helm package manager
to assemble their configuration files into charts. The latter are
reusable packages of pre-configured Kubernetes resources that
can be deployed as a unit. In this paper, we aim to support chart
developers and users by carrying out a comprehensive study on
publicly available charts. For 9,482 charts that are distributed via
the Artifact Hub repository, we mine and collect the list of their
metadata, versions, dependencies, maintainers and container
images. Then, we carry out an empirical analysis to assess the
state and evolution of charts, as well as the outdatedness and
security risks of their images. We found that the ecosystem
forming around Helm charts is growing fast. However, most of
the charts are not official with no popularity and no license. We
also observed that charts tend to release multiple versions, but
around half of them are still in the initial development phase.
When looking at the container images used in charts, we found
that around half of them are outdated and 88.1% of them are
exposed to vulnerabilities, jeopardizing 93.7% of the charts.
