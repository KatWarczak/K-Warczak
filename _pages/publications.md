---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
Below is a list of selected publications and preprints. For a full list of my publications please see [my Google Scholar page](https://scholar.google.com/citations?user=HTLatcMAAAAJ&hl=en).


<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

