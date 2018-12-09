### Saturday

{% for event in site.data.schedule_sat %}
- **{{ event.time }}:** {{ event.event }}
{% endfor %}

### Sunday

{% for event in site.data.schedule_sun %}
- **{{ event.time }}:** {{ event.event }}
{% endfor %}
