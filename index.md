---
layout: default
title: Home
notitle: true

# groups of columns of {roles: list, width: num, image: bool}
role-tables:
- - roles: [faculty, postdoc]
    width: 6
    image: true
  - roles: [grad, visit]
    width: 6
    image: true
- - roles: [alum]
    width: 6
    image: false

---

<div class="jumbotron">
    <p>
Psychological Health and Imaging group (PHI) develops neuroimaging and electrical physiology technologies for improving the evaluation, diagnosis, and treatment of mental health problems. With a multidisciplinary team of engineers, statisticians, psychiatrists, and psychologists, we are currently focusing on brain developments in children and adolescents with mental disorders and cross-disease psychiatric neuroimaging. Our team also takes charge of the Neuroimaging Center of Shanghai Mental Health Center, managing the acquisition, processing, and sharing of thousands of psychiatric neuroimaging data. We welcome researchers to join or visit us.
    </p>
</div>

<section>
    <h2>News</h2>
    <ul class="news list-unstyled">
        {% for post in site.posts limit: site.front_page_news %}
            {% include news-item.html item=post %}
        {% endfor %}
    </ul>
    {% assign numposts = site.posts | size %}
    {% if numposts >= 1 %}
        <p>
            <span class="fa fa-fw fa-history"></span>
            <a href="{{ site.base }}/blog.html">Older posts&hellip;</a>
        </p>
    {% endif %}
</section>

