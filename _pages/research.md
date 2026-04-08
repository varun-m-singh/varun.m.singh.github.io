---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into two main areas: geotechnical earthquake engineering with a focus on liquefaction-induced ground failure, and the advancement of predictive models for soil settlement and landslide mitigation. One strand of research in this first area explores how liquefaction affects existing structures, particularly through the mechanics of lateral spreading. My interest in seismic hazards also informs projects evaluating the real-world efficacy of standard predictive models, using historical data like the 2011 Christchurch earthquake to understand how complex stratigraphy and geomorphic boundaries condition soil failure.

My other main research agenda uses advanced geotechnical and spatial data to develop optimized hazard assessment frameworks. One major project leverages high-resolution Cone Penetration Test (CPT) case histories and remote sensing to optimize the Lateral Displacement Index (LDI) to improve on the systematic biases and false-positive predictions that traditionally limit urban-scale assessments.

In a related avenue of research, I am bridging the gap between structural and geotechnical engineering by exploring soil settlement predictions using field testing data, gaining insight into accelerated mitigation methods for emergency and disaster-recovery projects.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
