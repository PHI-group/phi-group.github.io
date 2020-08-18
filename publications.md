---
layout: default
title: Publications
---

<div class="card-columns">
    {% comment %}
    Sort the publications by date, putting those without dates last
    {% endcomment %}
    {% assign publications_by_date = site.publications | sort: 'last-updated', 'first' %}
    {% assign publications_by_date = publications_by_date | reverse %}
    {% for p in publications_by_date %}
        {% include publication-card.html publication=p %}
    {% endfor %}
</div>

