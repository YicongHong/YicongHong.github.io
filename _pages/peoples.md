---
layout: page
title: People
permalink: /peoples/
id: "peoples"
---

# People

something

## Faculty

<div class="flex-container people image-container">
{% for person in site.data.peoples %}
  {% include person_image image=person.image caption=person.name link=person.website title=person.name %}
{% endfor %}
</div>
