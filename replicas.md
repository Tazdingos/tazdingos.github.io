---
layout: default
---

[[ Kontakt ]](/) [[ Kläder ]](/clothes) [[ Replikor ]](/replicas) [[ Accessoarer ]](/accessories) [[ Antika vapen ]](/antique_weapons)


{% for item in site.replicas -%}
[[ {{ item.name }} ]](#{{ item.name | downcase }})
{% endfor %}

----

{% for item in site.replicas %}
### {{ item.name }}
  {{ item.description }}
  {{ item.content }}
----
{% endfor %}
