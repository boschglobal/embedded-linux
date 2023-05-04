{% macro link_tile_wall() -%}
<div class="link-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro link_tile(title, description, link, img_src, color='purple') -%}
<a class="link-tile tile-{{ color }}" title="{{ description }}" href="{{ link }}">
    <div class="tile-content">
        <span>
        <div class="link-tile-image">
        <img src="{{ img_src }}" alt="{{ title }}" />
        </div>
        <p>{{ title }}</p>
        </span>
    </div>
</a>
{%- endmacro %}

{% macro contact_tile_wall() -%}
<div class="contact-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro contact_tile(name, function, email, color='green') -%}
<a class="contact-tile tile-{{ color }}" href="mailto:{{ email }}">
    <div class="tile-content">
        <span>
        <p class="contact-tile-name">{{ name }}</p>
        <p class="contact-tile-function">{{ function }}</p>
        <p class="contact-tile-email">{{ email }}</p>
        </span>
    </div>
</a>
{%- endmacro %}

{% macro contact_tile_image(img_src, text, link, color='green') -%}
<a class="contact-image-tile" href="{{ link }}">
    <div class="tile-content">
        <img src="{{ img_src }}" alt="{{ text }}" />
    </div>
</a>
{%- endmacro %}