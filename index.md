---
layout: default
title: Home
---

# Programming Language Library

## Registered Languages

{% for lang in site.data.languages %}
<div style="border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; border-radius: 5px;">
  <h3>{{ lang.name }}</h3>
  <p>
    <a href="{{ lang.website }}" target="_blank">Website</a> | 
    <a href="{{ lang.repo }}" target="_blank">GitHub</a>
  </p>
</div>
{% endfor %}
