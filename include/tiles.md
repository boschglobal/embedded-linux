{% macro tile_wall() -%}
<div class="tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro tile(title, description, link, img_src, color='purple') -%}
<a class="tile tile-{{ color }}" title="{{ description }}" href="{{ link }}">
    <div class="tile-content">
        <span>
        <div class="tile-image">
        <img src="{{ img_src }}" alt="{{ title }}" />
        </div>
        <p>{{ title }}</p>
        </span>
    </div>
</a>
{%- endmacro %}