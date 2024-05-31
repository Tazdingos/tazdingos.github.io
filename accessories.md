---
layout: default
---
{% for accessory in site.accessories -%}
[{{ accessory.name }}](#{{ accessory.name | downcase }})
{% endfor %}

----

{% for accessory in site.accessories %}
### {{ accessory.name }}
  {{ accessory.description }}
  {{ accessory.content }}
----
{% endfor %}
