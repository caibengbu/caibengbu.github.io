---
layout: archive
permalink: /software/
title: "Software"
author_profile: true
---

{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}

- [Coefplots.jl](https://github.com/caibengbu/Coefplots.jl)
- [GLFixedEffectModels.jl](https://github.com/jmboehm/GLFixedEffectModels.jl)