---
layout: home
title: Success is a path for all
description: 
background: /assets/theme/images/gaman-alice-tescud904NY-unsplash.jpg
permalink: /
---
{% for section in site.sections %}
  <h2>{{ section.name }}</h2>
  <p>{{ section.content | markdownify }}</p>
{% endfor %}

[Petridish](https://github.com/peterdesmet/petridish) is a Jekyll theme for research project websites. Or your personal blog or lab website. 👩‍🔬 It's mobile-friendly (thanks to [Bootstrap 5](https://getbootstrap.com/docs/5.1/)), free, easy to customize, and designed to work well with [GitHub Pages](https://pages.github.com/).

## Installation

See the demo website for instructions:

- [Installation]({{ '/docs/installation/' | relative_url }})
- [Configuration]({{ '/docs/configuration/' | relative_url }})
- [Markdown]({{ '/docs/markdown/' | relative_url }})
