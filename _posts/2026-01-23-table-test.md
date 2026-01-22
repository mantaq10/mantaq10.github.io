---
title: Table Test
date: 2026-01-23 01:04 +0500
---
{% assign row = site.data.authors[0] %}
{{ row | inspect }}

{{ row["First name"] }}
{{ row["Last name"]  }}


{% assign row = site.data.authors[0] %}
{% for pair in row  %}
    {{pair | inspect }}
{% endfor %}


<table>
    {% for row in site.data.authors  %}
        {% if forloop.first %}
        <tr>
            {% for pair in row %}
                <th> {{ pair[0] }}</th>
            {% endfor %}
        </tr>
        {% endif %}

        {% for tablerow pair in row %}
            {{ pair[1] }}
        {% endtablerow %}
    {% endfor %}        
</table>