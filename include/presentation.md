{% macro overview(metadata) -%}

<h1>{{ metadata.topic }}</h1>

<p>
    By <strong>{{ metadata.presenter }}</strong> of <strong>{{
    metadata.affiliation }}</strong><br/>
    Time: <strong>{{ metadata.time }}</strong>&nbsp;
    Room: <strong>{{ metadata.room }}</strong>
</p>

{%- if metadata.abstract -%}
<h2>Abstract</h2>
<p>
    {{ metadata.abstract }}
</p>
{% endif %}

{%- if metadata.biography -%}
<h2>Biography</h2>
<p>
    {{ metadata.biography }}
</p>
{% endif %}

{% endmacro %}