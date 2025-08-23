
---
layout: default
title: "Statistical Consulting & Teaching"
---

## Consulting

I provide statistical consulting for university-affiliated students, staff, and faculty. Typical topics include study design, power/sample size, regression and mixed models, generalized models, GAMs, multilevel/hierarchical analysis, time series, and reproducible workflows in R.

- **Appointments:** See the [Schedule](./schedule) page.
- **Contact:** {{ site.consultant.email }}

## Ground Rules
{% include ground_rules.md %}

## Course Materials {#downloads}
Below are commonly requested downloads. Instructors/students can link here directly.

<ul class="download-list">
{% for d in site.data.downloads %}
  <li class="download-item">
    <a class="download-link" href="{{ d.file | relative_url }}">{{ d.title }}</a>
    <div class="download-desc">{{ d.desc }}</div>
  </li>
{% endfor %}
</ul>
