---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{ author.googlescholar }}).
{% endif %}

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
