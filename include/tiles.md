{% macro link_tile_wall() -%}
<div class="link-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro link_tile(title, description, link, img_src, color='purple') -%}
<a class="link-tile tile-{{ color }}" title="{{ description }}" href="{{ link }}">
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