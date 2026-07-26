---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

We use computation and AI to understand materials at the atomic level and to design and discover new materials for critical technologies — from energy storage to computing and more.

We strive to achieve the following in **our Research**:

* **Gain physical insights** — We strive to understand critical materials that exhibit truly exceptional properties, requiring insights achieved at the atomic level through computation.
* **Devise guiding principles** — Through predictive computation, we devise principles that can guide the design, selection, and engineering of materials to achieve desired properties.
* **Invent novel materials** — The predictive power of first-principles computation lets us identify new materials with better performance in an accelerated, inexpensive, and scalable manner — many of them critical to enabling better technologies.
* **Generate high-quality data** — We produce high-quality computational data that the broader community can use to develop better AI/ML models.
* **Advance AI/ML for science** — We develop AI/ML methods, benchmarks, and models that advance scientific research more broadly.


Research Areas
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
