---
layout: default
title: Resources
---

<div class="card-columns">
    {% comment %}
    Sort the resources by date, putting those without dates last
    {% endcomment %}
    {% assign resources_by_date = site.resources | sort: 'last-updated', 'first' %}
    {% assign resources_by_date = resources_by_date | reverse %}
    {% for p in resources_by_date %}
        {% include resource-card.html resource=p %}
    {% endfor %}
</div>
