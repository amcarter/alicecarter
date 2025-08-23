---
layout: default
title: "Alice Carter's stats consulting & teaching pages"
---

## Consulting

I provide statistical consulting for Ecology Center grad students, postdocs, and faculty. Typical topics include study design, power/sample size, regression and mixed models, generalized models, GAMs, multilevel/hierarchical analysis, time series analysis.

Before you book, please review the **ground rules**:
{% include ground_rules.md %}

**Appointments:** See my [Calendar](https://calendly.com/usu_ec_statistical_consulting).<br>
**Contact:** <a href="mailto:{{ site.consultant.email }}">{{ site.consultant.email }}</a>

## Example Scripts {#downloads}

<ul class="download-list">
{% for d in site.data.downloads %}
  <li class="download-item">
    <a class="download-link" href="{{ d.file | relative_url }}">{{ d.title }}</a>
    <div class="download-desc">{{ d.desc }}</div>
  </li>
{% endfor %}
</ul>
