{% macro link_tile_wall() -%}
<div class="link-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro link_tile(title, description, link, img_src, color='purple') -%}
<a class="link-tile tile-{{ color }}" title="{{ description }}" href="{{ link }}">
    <div class="tile-content">
        <div class="tile-image">
        <img src="{{ img_src }}" alt="{{ title }}" />
        </div>
        <p>{{ title }}</p>
    </div>
</a>
{%- endmacro %}


{% macro contact_tile_wall() -%}
<div class="contact-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro contact_tile(name, function, email, link, color='green') -%}
<a class="contact-tile tile-{{ color }}" href="{{ link }}">
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


{% macro presentation_tile_wall() -%}
<div class="presentation-tile-wall">
    {{ caller() }}
</div>
{%- endmacro %}

{% macro presentation_tile(metadata, id, color='grey-green') -%}
{% set data = metadata[id] %}
<a class="presentation-tile tile-{{ color }}" href="{{ id }}">
    <div class="tile-content">
        <span>
        <h3>{{ data.topic }}</h3>
        <p><strong>{{ data.presenter }}</strong> | <strong>{{ data.affiliation }}</strong><br/>
        Time: <strong>{{ data.time }}</strong> &nbsp; Room: <strong>{{ data.room }}</strong></p>
        </span>
    </div>
</a>
{%- endmacro %}

{% macro presentation_time_tile(time, color='grey') -%}
<a class="presentation-time-tile tile-{{ color }}">
    <div class="tile-content">
        <h3>{{ time }}</h3>
    </div>
</a>
{%- endmacro %}