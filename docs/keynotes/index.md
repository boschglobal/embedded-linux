---
title: Keynotes
hide:
  - toc
---

# Keynotes

{% import 'tiles.md' as tiles %}

All keynotes take place in the Auditorium and last between 10 and 15 minutes.

{% call tiles.presentation_tile_wall() %}

  {{ tiles.presentation_tile_new(
    metadata=presentations['siemens'],
    link='siemens'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'To be defined', 
    topic = 'To be defined', 
    affiliation = 'Suse', 
    time = '10:30', 
    room = 'Auditorium', 
    link = 'suse'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Ana Jiménez Santamaría', 
    topic = 'To be defined', 
    affiliation = 'TODO Group', 
    time = '10:45', 
    room = 'Auditorium', 
    link = 'todo_group'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Mirko Boehm', 
    topic = 'Public Policies: Influence from the EU', 
    affiliation = 'Linux Foundation', 
    time = '11:00', 
    room = 'Auditorium', 
    link = 'linux_foundation'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Jan Lübbe (CTO)', 
    topic = 'Community Collaboration Patterns: Addressing Risk and Complexity', 
    affiliation = 'Pengutronix', 
    time = '11:15', 
    room = 'Auditorium', 
    link = 'pengutronix'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Dr. Matthias Klauda (XC/EE)', 
    topic = 'The importance of open source culture at Bosch', 
    affiliation = 'Robert Bosch GmbH', 
    time = '14:30', 
    room = 'Auditorium', 
    link = 'bosch'
  ) }}

{% endcall %}