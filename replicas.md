---
layout: default
---
{% for item in site.replicas -%}
[{{ item.name }}](#{{ item.name | downcase }})
{% endfor %}

----

{% for item in site.replicas %}
### {{ item.name }}
  {{ item.description }}
  {{ item.content }}
----
{% endfor %}
