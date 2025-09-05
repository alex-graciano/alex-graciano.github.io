---
layout: home
title: Alex Graciano
description: "Computer scientist and researcher specializing in real-time 3D visualization and geoscientific applications."
image: /assets/images/profile.jpeg
---

<!-- The content below will appear below the title on the homepage -->

{% if page.description %}
<p>{{ page.description }}</p>
{% endif %}

{% if page.image %}
<img src="{{ page.image | relative_url }}" alt="Alex Graciano" style="max-width:200px;margin-bottom:1em;">
{% endif %}