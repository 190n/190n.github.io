{% if site.data.sponsors.platinum.size > 0 %}
### Platinum

{% for sp in site.data.sponsors.platinum %}
[![{{ sp.name }}](/img/logos/{{ sp.logo }})]({{ sp.url}})
{% endfor %}

{% endif %}
{% if site.data.sponsors.gold.size > 0 %}
### Gold

{% for sp in site.data.sponsors.gold %}
[![{{ sp.name }}](/img/logos/{{ sp.logo }})]({{ sp.url}})
{% endfor %}

{% endif %}
{% if site.data.sponsors.silver.size > 0 %}
### Silver

{% for sp in site.data.sponsors.silver %}
[![{{ sp.name }}](/img/logos/{{ sp.logo }})]({{ sp.url}})
{% endfor %}

{% endif %}
{% if site.data.sponsors.bronze.size > 0 %}
### Bronze

{% for sp in site.data.sponsors.bronze %}
[![{{ sp.name }}](/img/logos/{{ sp.logo }})]({{ sp.url}})
{% endfor %}

{% endif %}
