---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

Our Vision
======
We are a research group specializing in computational materials science. We aim to gain insights into critical materials phenomena by understanding materials at the atomistic level, combined with predictive computational modeling for materials discovery and innovation. This includes designing and discovering new materials with exceptional performance, overcoming materials limitations in critical technologies (e.g., energy, efficiency, computing), and accelerating the innovation of new technologies driven by new materials.

Our Approach
======
The properties and behavior of materials are predicted through computation based on the first-principles laws governing atomic interactions. Our research employs atomistic modeling techniques ranging from ab initio methods, molecular dynamics simulations, and Monte Carlo to large-scale atomistic modeling, combined with multi-scale approaches. We also leverage state-of-the-art high-performance computing, AI/machine learning, and quantum computing to accelerate our research in a scalable, cost-effective manner.

<blockquote class="pull-quote">The underlying physical laws necessary for the mathematical theory of a large part of physics and the whole of chemistry are thus completely known, and the difficulty is only that the exact application of these laws leads to equations much too complicated to be soluble.<cite>— Paul Dirac</cite></blockquote>

With the aid of fast computation, we can tackle complex materials problems at unprecedented levels.

<blockquote class="pull-quote">The invention of silicon circuits and lithium ion batteries made computers and iPods and iPads possible, but it took years to get those technologies from the drawing board to the marketplace. We can do it faster.<cite>— Barack Obama, on the Materials Genome Initiative</cite></blockquote>

The ability to predictively compute materials properties is critical to this vision of accelerated materials design, discovery, development, and deployment.

Our Research
======
* **Gain physical insights** — We strive to understand critical materials that exhibit truly exceptional properties, requiring insights achieved at the atomic level through computation.
* **Devise guiding principles** — Through predictive computation, we devise principles that can guide the design, selection, and engineering of materials to achieve desired properties.
* **Invent novel materials** — The predictive power of first-principles computation lets us identify new materials with better performance in an accelerated, inexpensive, and scalable manner — many of them critical to enabling better technologies.

Examples of Our Research
======

{% include base_path %}

{% assign research_sorted = site.research | sort: "order" %}
<div class="card-grid">
{% for topic in research_sorted %}
  <div class="info-card">
    <div class="card-icon"><i class="fas fa-{{ topic.icon }}" aria-hidden="true"></i></div>
    <h4><a href="{{ base_path }}{{ topic.url }}">{{ topic.title }}</a></h4>
    <p>{{ topic.excerpt }}</p>
  </div>
{% endfor %}
</div>
