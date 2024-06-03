---
theme: simple
title: Slides
layout: default
---

{% assign sorted_slides = site.data.slides | sort: "year" | reverse %}
{% for pub in sorted_slides %}
<ul>
    <li>
        <a href="{{ pub.url }}" target="_blank">{{ pub.title }}</a> - <small><em>{{ pub.date }}{{ pub.year }}</em></small><br>
        {% if pub.event.url %}
          <small><a href="{{ pub.event.url }}" target="_blank">{{ pub.event.name }}</a></small>
        {% else %}
          <small><em>{{ pub.event.name }}</em></small>
        {% endif %}
    </li>
</ul>
{% endfor %}