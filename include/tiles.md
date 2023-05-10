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

{% macro presentation_tile(presenter, topic, affiliation, time, room, link, color='grey-green') -%}
<a class="presentation-tile tile-{{ color }}" href="{{ link }}">
    <div class="tile-content">
        <span>
        <h3 class="presentation-tile-topic">{{ topic }}</h3>
        <p><strong>{{ presenter }}</strong> | <strong>{{ affiliation }}</strong><br/>
        <strong>Time</strong>: {{ time }} &nbsp; <strong>Room</strong>: {{ room }}</p>
        </span>
    </div>
</a>
{%- endmacro %}

{% macro presentation_tile_new(metadata, link, color='grey-green') -%}
<a class="presentation-tile tile-{{ color }}" href="{{ link }}">
    <div class="tile-content">
        <span>
        <h3 class="presentation-tile-topic">{{ metadata.topic }}</h3>
        <p><strong>{{ metadata.presenter }}</strong> | <strong>{{ metadata.affiliation }}</strong><br/>
        <strong>Time</strong>: {{ metadata.time }} &nbsp; <strong>Room</strong>: {{ metadata.room }}</p>
        </span>
    </div>
</a>
{%- endmacro %}