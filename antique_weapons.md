---
layout: default
---
{% for item in site.antique_weapons -%}
[{{ item.name }}](#{{ item.name | downcase }})
{% endfor %}

----

{% for item in site.antique_weapons %}
### {{ item.name }}
  {{ item.description }}
  {{ item.content }}
----
{% endfor %}
