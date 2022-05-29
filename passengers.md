# Passenger list

{% for item in site.data.titanic %}
- {{ item.Name }} was {{ item.Age }} years old.
{% endfor %}
