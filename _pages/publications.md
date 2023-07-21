---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
{% endif %}

Publications:  [2023](#2023)

<hr>

{% include base_path %}

### 2023

{% for post in site.publications reversed %}
  {%if post.pub_year == '2023' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
