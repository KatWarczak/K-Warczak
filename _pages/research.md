---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/profile.png"
---
Engineerable biological systems have the potential to be some of our greatest tools against a host of problems, from biological and chemical threats to human health, to food insecurity, and the sustainable production of materials. Understanding the fundamental building blocks of complex biological systems and their interactions lies at the heart of creating biological tools that can function robustly, predictably, and with quantitative precision. However, the fundemental knowledge and high-thoughput techniques to select ideal biocatalysts, reaction conditions, and production platforms are limited.

The open nature of cell-free systems enables this work though a modular approach to biological transformations that allows for distinct biological components to be characterized rapidly and with precise control of the chemical environment. These methods reconceptualize how biological systems are engineered for applications in health, materials, and energy. Instead of making concessions between the cell’s physiological and evolutionary objectives compared to engineerable objectives. In this manner we are able to rapidly test components and conditions, port them to cellular chassis, or use them directy in cell-free biomanufacuring platforms. 

My lab will focus on developing new strategies that expand our traditional models of biomanufacturing by taking a data-driven and multiplexed approach to elucidate fundamental principles that allow for scalable cell-free synthetic biology.

<p align='center'>
<img src='/images/Current_work_melanin.png' width='900'>
</p>

My current project focuses on the use protein language models to interrogate substrate specificity and promiscuity of novel biocatalysts using the melanin as a model system towards large-scale production of biological polymers.


My future work will focus on three key projects to take a holistic approach to generating the tools and fundemental knowledge to develop cell-free systems as scalable biomanufacturing platforms and research tools: computationally driven design of biosensors, machine learning-enabled materials production, and fundamental explorations of cell-free metabolism towards small molecule production. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}