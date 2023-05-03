{% macro img_shadow(src, alt, width='100%') -%}
<img class="img-shadow" src="{{ src }}" alt="{{ alt }}" style="width: {{ width }};">
{%- endmacro %}
