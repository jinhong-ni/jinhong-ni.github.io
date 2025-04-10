---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
{% endif %}

Publications:  [2025](#2025)

<hr>

{% include base_path %}

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
