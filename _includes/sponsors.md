{% if site.data.sponsors.platinum.size > 0 %}
### Platinum

{% for sp in site.data.sponsors.platinum %}
<a href="{{ sp.url }}" target="_blank">
    <img src="/img/logos/{{ sp.logo }}" class="logo logo-platinum" alt="{{ sp.name }}" title="{{ sp.name }}">
</a>
{% endfor %}

{% endif %}
{% if site.data.sponsors.gold.size > 0 %}
### Gold

{% for sp in site.data.sponsors.gold %}
<a href="{{ sp.url }}" target="_blank">
    <img src="/img/logos/{{ sp.logo }}" class="logo logo-gold" alt="{{ sp.name }}" title="{{ sp.name }}">
</a>{% endfor %}

{% endif %}
{% if site.data.sponsors.silver.size > 0 %}
### Silver

{% for sp in site.data.sponsors.silver %}
<a href="{{ sp.url }}" target="_blank">
    <img src="/img/logos/{{ sp.logo }}" class="logo logo-silver" alt="{{ sp.name }}" title="{{ sp.name }}">
</a>
{% endfor %}

{% endif %}
{% if site.data.sponsors.bronze.size > 0 %}
### Bronze

{% for sp in site.data.sponsors.bronze %}
<a href="{{ sp.url }}" target="_blank">
    <img src="/img/logos/{{ sp.logo }}" class="logo logo-silver" alt="{{ sp.name }}" title="{{ sp.name }}">
</a>
{% endfor %}

{% endif %}
