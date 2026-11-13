---
layout: default
title: Havelock-Vance Lab
---

# Havelock-Vance Lab

We develop machine learning methods for environmental and ecological observation
systems. Our work spans spatiotemporal forecasting, remote sensing, and
scientific computing.

## Publications

{% for paper in site.publications %}
- **{{ paper.title }}** — {{ paper.venue }}, {{ paper.year }}.
{% endfor %}
