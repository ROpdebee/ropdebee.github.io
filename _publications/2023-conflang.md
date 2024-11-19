---
title: "Ansible Is Turing Complete"
collection: publications
permalink: /publication/2023-conflang
published_prefix: 'Unpublished presentation abstract'
date: 2023-10-24
venue: 2nd Workshop on Configuration Languages (CONFLANG'23)
venue_abbrev: CONFLANG'23
pdf_url: 'https://researchportal.vub.be/files/106024645/main.pdf'
citation: 'Opdebeeck, R., & De Roover, C. (2023). <i>Ansible Is Turing Complete.</i> Abstract from 2nd Workshop on Configuration Languages, Cascais, Portugal.'
related_talks:
    - name: Ansible Is Turing Complete
      slug: 2023-conflang
---

Unsurprisingly, many systems and languages are Turing complete. An interesting subset is that of systems which are Turing complete by accident [1]. A well-known example is that of C++ templates, which led to the practice of template metaprogramming. A more creative showcase of accidental Turing completeness can be found in Cities: Skylines [2], involving the flow of simulated city sewage to construct a 4- bit adder. More recently, it has been shown that Helm charts, which abstract over Kubernetes deployments, are Turing com- plete due to the inclusion of the go-template language [3]. This led some to suggest that every simple language eventually ends up Turing complete [3].
Although difficult to argue that it is a “simple” language [4], [5], Ansible is a popular configuration management language and widely used in practice [6]. At first glance, Ansible does not appear to offer language features that make it truly Turing complete. While it supports conditional and looping execution, such loops can only be executed over a finite sequence of elements. Nonetheless, one can envision various paths to Turing completeness in Ansible. A trivial path would be that of plugins, which allow developers to extend Ansible functionality through Python code. Thus, one could “cheat” by leveraging the Turing completeness of Python. Alternatively, Jinja2, embedded into Ansible as a templating language, could well be Turing complete, similar to the aforementioned embedding of go-template in Helm charts.
In this presentation, rather than relying on the Turing completeness of other languages, we instead show that we can achieve Turing completeness relying solely on a tiny subset of the core Ansible language. The presentation is structured into three parts, which are briefly described in the following sections.
