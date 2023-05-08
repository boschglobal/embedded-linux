{% macro img_shadow(src, alt, width='auto', max_width='auto') -%}
<img class="img-shadow" src="{{ src }}" alt="{{ alt }}" style="width: {{ width }}; max-width: {{ max_width }};">
{%- endmacro %}
