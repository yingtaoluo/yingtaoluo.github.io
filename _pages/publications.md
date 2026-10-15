---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{ author.googlescholar }}).
{% endif %}

## Research Directions

<div style="max-width: 780px;" markdown="1">

| Research Area | Active Period |
|:---|:---|
| **LLM Agents & LLM Training** | 2024–Present |
| **Recommender Systems & User Modeling** | 2021–Present |
| AI for Healthcare | 2021–2026 |
| Time Series | 2021–2024 |
| AI for Science | 2020–2024 |

</div>

---

<div class="pub-page">
{% for section in site.data.publications %}
<section class="pub-section" id="{{ section.id }}">
<h2 class="pub-section-title">{{ section.title }}</h2>
{% for paper in section.papers %}
{% include publication-item.html paper=paper %}
{% endfor %}
</section>
{% endfor %}
<p class="pub-footnote"><span><sup>*</sup> Equal contribution</span><span>&lt;...&gt; Additional presentation at a workshop</span></p>
</div>
