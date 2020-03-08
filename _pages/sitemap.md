---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: false
sidebar:
  nav: pages
---

<!-- <h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %} -->

## Posts

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

## IP Cores

{% for post in site.cores %}
  {% include archive-single.html %}
{% endfor %}

<!-- ## Standard Cell Libraries

{% for post in site.std_cell_libs %}
  {% include archive-single.html %}
{% endfor %}
 -->
<!-- {% capture written_label %}'None'{% endcapture %} -->

<!-- {% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% capture metadata %}{{ collection.metadata }}{% endcapture %}
    {% if label != written_label %}
<h2>{{ label }} - {{ metadata }}</h2>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
      {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %} -->