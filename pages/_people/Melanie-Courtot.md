---
title: "Melanie Courtot"
layout: default
date: 2018-12-12
excerpt_separator: <!--more-->
image_file: 'courtot_melanie_web_2015_2.jpg'
category:
  - people
  - contact
tags:
  - contacts
  - contributors
  - leads
  - CP
  - .featured
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

European Bioinformatics Institute  
Samples, Phenotypes and Ontologies  
BioSamples/GA4GH Project Lead   
Co-lead SchemaBlocks initiative  

<!--more-->

email [courtot@ebi.ac.uk](mailto:courtot@ebi.ac.uk)  
web [EBI](https://www.ebi.ac.uk/about/people/melanie-courtot)  
