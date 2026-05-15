---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## Pages

- [About]({{ base_path }}/)
- [Publications]({{ base_path }}/publications/)
- [Blog Posts]({{ base_path }}/year-archive/)
- [Gallery]({{ base_path }}/gallery/)
- [CV]({{ base_path }}/cv/)

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

## Blog Posts

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
