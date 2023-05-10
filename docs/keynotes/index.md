---
title: Keynotes
hide:
  - toc
---

# Keynotes

{% import 'tiles.md' as tiles %}

All keynotes take place in the Auditorium and last between 10 and 15 minutes.

{% call tiles.presentation_tile_wall() %}
  {% for key in keynotes %}
    {{ tiles.presentation_tile(metadata=keynotes, id=key) }}
  {% endfor %}
{% endcall %}