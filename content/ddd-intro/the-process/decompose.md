---
title: "3. Decompose"
date: 2020-08-20T01:16:48+01:00
draft: false
weight: 3
---

Decompose the domain into sub-domains - loosely-coupled parts of the domain.

We decompose a large problem domain into sub-domains for a few key reasons:

- reduced cognitive load, so that we can reason about parts of the domain independently,
- give development teams autonomy, so that they can work on separate parts of the solution,
- identifying loose-coupling and high-cohesion in the domain which carries over to our software architecture and team structure.

As a starting point, we recommend carving up your event storm into sub-domains and [Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps).

![Sub-domains on an EventStorm](../resources/event_storm_sub_domains.png)*Credit: Alberto Brandolini*

#### Tools

- [Business Capability Modelling](https://www.slideshare.net/trondhr/from-capabilities-to-services-modelling-for-businessit-alignment-v2)
- [Design Heuristics](https://www.dddheuristics.com/)
- [EventStorming with sub-domains](https://www.eventstorming.com/)
- [Independent Service Heuristics](https://github.com/TeamTopologies/Independent-Service-Heuristics)
- [Visualising Sociotechnical Architecture with Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge
