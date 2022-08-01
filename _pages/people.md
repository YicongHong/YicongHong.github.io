---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

# People

something

## Faculty

<div class="flex-container people image-container">
{% for person in site.data.people %}
  {% include person_image image=person.image caption=person.name link=person.website title=person.name %}
{% endfor %}
</div>
