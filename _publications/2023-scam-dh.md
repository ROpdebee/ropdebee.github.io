---
title: "The Docker Hub Image Inheritance Network: Construction and Empirical Insights"
collection: publications
permalink: /publication/2023-scam-dh
date: 2023-10-01
venue: Proceedings of the 23rd IEEE International Working Conference on Source Code Analysis and Manipulation (SCAM'23)
venue_abbrev: SCAM'23
preprinturl: 'https://soft.vub.ac.be/Publications/2023/vub-tr-soft-23-14.pdf'
citation: "Opdebeeck, R., Lesy, J., Zerouali, A. & De Roover, C. (2023). <i>The Docker Hub Image Inheritance Network: Construction and Empirical Insights</i> In Proceedings of the 23rd IEEE International Working Conference on Source Code Analysis and Manipulation (SCAM'23)."
doi: 10.1109/SCAM59687.2023.00029
related_talks:
    - name: 'The Docker Hub Image Inheritance Network: Construction and Empirical Insights'
      slug: '2023-scam-dh'
---
Docker is a popular technology to containerise applications together with their dependencies into reproducible environments. In Docker, container images can depend on others through inheritance. Such inheritance can propagate bad practices and security vulnerabilities from a parent image to its children. Unfortunately, Docker Hub, the most popular online registry of images, lacks transparency about such inheritance. This obscures the software supply chain, possibly leaving image users unaware of quality or security issues caused by parent images. Nonetheless, we found inheritance on Docker Hub to be an understudied topic in academia to date. Therefore, the goal of this paper is to empirically investigate the practice of image inheritance on Docker Hub. To this end, we collect a dataset of 636,625 unique images belonging to popular Docker repositories and identify inheritance by comparing the images’ layers. We leverage the constructed inheritance network to empirically investigate three aspects, namely the structure of the inheritance network, how child images differ from their parents, and outdatedness of parent images. Our results show that most popular community Docker Hub images directly inherit from official images rather than other community ones. We also observe that community child images are often much larger than their parent, in comparison to official child images. This may indicate the existence of gaps between the features provided by official images and those required by consumers, suggesting the need for more ready-made parent images. Finally, we find that around half of the child images use an outdated parent image at the time the child is built, although time lag is usually less than a month. However, time lag becomes much larger when we compare against the latest version of the parent image available at the analysis date, with up to 70% of child images using an outdated parent image and a median of over 5 months of time lag. This indicates that users should pay attention to the lineage of the images they consume, and motivates future work on alleviating technical lag in Docker images.
