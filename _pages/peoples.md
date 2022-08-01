---
layout: page
title: People
group: "navigation"
id: "people"
---

# People

something

## Faculty

<div class="flex-container people image-container">
{% for person in site.data.peoples %}
  {% include person_image image=person.image caption=person.name link=person.website title=person.name %}
{% endfor %}
</div>
