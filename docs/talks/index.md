---
title: Talks
hide:
  - toc
---

# Talks / Presentations

{% import 'tiles.md' as tiles %}

Talks (presentations) will take place in smaller rooms in parallel to the market
place. Each talk will last about 20 min. plus 5 min. discussion time.

The location of each meeting room is found on the [floor
plan](../venue#floor-plan).

## 

{% set ns = namespace(old_time='') %}
{% call tiles.presentation_tile_wall() %}
  {% for key, value in talks.items() %}
    {% if ns.old_time != value.time %}
      {{ tiles.presentation_time_tile(value.time) }}
    {% endif %}
    {{ tiles.presentation_tile(metadata=talks, id=key) }}
    {% set ns.old_time = value.time %}
  {% endfor %}
{% endcall %}