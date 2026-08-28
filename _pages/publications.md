---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %} -->
  You can find the full list of my articles on <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
<!-- {% endif %} -->

Publications:  [2026](#2026), [2025](#2025)

<hr>

{% include base_path %}

### 2026

{% for post in site.publications reversed %}
  {%if post.pub_year == '2026' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2025

{% for post in site.publications reversed %}
  {%if post.pub_year == '2025' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

### Preprint

{% for post in site.publications reversed %}
  {%if post.pub_year == 'preprint' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
