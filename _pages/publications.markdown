---
theme: simple
layout: default
title: 'Publicações'
---

{% assign sorted_publications = site.data.publications | sort: "year" | reverse %}
{% for pub in sorted_publications %}
<ul>
    <li>
        <a href="https://doi.org/{{ pub.doi }}" target="_blank">{{ pub.title }}</a> <small>({{ pub.year }})</small><br/>
        <em><small>{{ pub.authors }}</small></em><br/>
        <small><a href="{{ pub.published_in.url }}" target="_blank">{{ pub.published_in.name }}</a> - {{ pub.type }}</small><br/>
    </li>
</ul>
{% endfor %}