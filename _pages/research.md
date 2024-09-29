---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/profile.png"
---
Engineerable biological systems have the potential to be some of our greatest tools against a host of problems, from biological and chemical threats to human health, to food insecurity, and the sustainable production of materials. Understanding the fundamental building blocks of complex biological systems and their interactions lies at the heart of creating biological tools that can function robustly, predictably, and with quantitative precision.

 In my work, I utilize the tools of cell-free synthetic biology to perform high-throughput characterization of cell-free biological systems with the goal of both understanding their fundamental function and improving their ability to generate novel mechanisms for biological sensing and biological production. The open nature of cell-free systems enables a modular approach to biological transformations enabling distinct biological components to be characterized rapidly and with precise control of the chemical environment. 

<p align='center'>
<img src='/images/Current_work_melanin.png' width='600'>
</p>

My current project focuses on the use protein language models to interrogate substrate specificity and promiscuity of novel biocatalysts using the biological polymer melanin as a model system.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
