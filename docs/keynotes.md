---
hide:
  - toc
---

{% import 'tiles.md' as tiles %}

# Keynotes

{% call tiles.presentation_tile_wall() %}

  {{ tiles.presentation_tile(
    'Matthias Klauda', 
    'To be defined', 
    'Robert Bosch GmbH', 
    '10:00', 
    'Auditorium', 
    'keynote_bosch'
  ) }}

  {{ tiles.presentation_tile(
    'Urs Gleim',
    'Living Open Source at Siemens',
    'Siemens AG',
    '10:15',
    'Auditorium',
    'keynote_siemens'
  ) }}

  {{ tiles.presentation_tile(
    'Marc Kleine-Budde', 
    'Community Collaboration Patterns: Addressing Risk and Complexity', 
    'Pengutronix', 
    '10:30', 
    'Auditorium', 
    'keynote_pengutronix'
  ) }}

  {{ tiles.presentation_tile(
    'Ana Jiménez Santamaría', 
    'To be defined', 
    'ToDo Group', 
    '10:45', 
    'Auditorium', 
    'keynote_todogroup'
  ) }}

  {{ tiles.presentation_tile(
    'Gabriele Columbro', 
    'Public Policies: Influence from the EU', 
    'Linux Foundation', 
    '11:00', 
    'Auditorium', 
    'keynote_linux_foundation'
  ) }}

  {{ tiles.presentation_tile(
    'Naveen Suryakumar', 
    'To be defined', 
    'Suse', 
    '11:15', 
    'Auditorium', 
    'keynote_suse'
  ) }}

{% endcall %}