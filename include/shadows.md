{% macro img_shadow(src, alt, width='auto') -%}
<img class="img-shadow" src="{{ src }}" alt="{{ alt }}" style="width: {{ width }};">
{%- endmacro %}
