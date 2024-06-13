---
layout: default
---
{% for item in site.clothes -%}
[{{ item.name }}](#{{ item.name | downcase }})
{% endfor %}

----

{% for item in site.clothes %}
### {{ item.name }}
  {{ item.description }}
  {{ item.content }}
----
{% endfor %}
