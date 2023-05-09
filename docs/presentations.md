---
hide:
  - toc
---

{% import 'tiles.md' as tiles %}

<!-- presenter, topic, affiliation, time, room, link  -->


# Talks/Presentations 

Talks (presentations) are held in different smaller rooms and last about 20 min.
plus 5 min. of discussion time.

{% call tiles.presentation_tile_wall() %}

  {{ tiles.presentation_tile(
    presenter = 'Dr. Christian Wege and David Schumm', 
    topic = 'SBOM Management at Scale', 
    affiliation = 'Mercedes Benz AG', 
    time = '11:30', 
    room = 'Sizi 2', 
    link = 'presentation_mercedes'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Naveen Suryakumar and Martin Wolf', 
    topic = 'Attaining nirvana on embedded devices with SUSE’s open-source solution', 
    affiliation = 'SUSE', 
    time = '11:30', 
    room = 'Sizi 5', 
    link = 'presentation_suse_1'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Naveen Suryakumar and Martin Wolf', 
    topic = 'Revolutionizing Edge Computing: Introducing SUSE Edge 2.0 for Scalable and Secure Infrastructures', 
    affiliation = 'SUSE', 
    time = '12:00', 
    room = 'Sizi 2', 
    link = 'presentation_suse_2'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Heike Jordan', 
    topic = 'To be defined', 
    affiliation = 'Emlix', 
    time = '12:30', 
    room = 'To be defined', 
    link = 'presentation_emlix'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Marc Kleine-Budde', 
    topic = 'To be defined', 
    affiliation = 'Pengutronics', 
    time = '13:00', 
    room = 'To be defined', 
    link = 'presentation_pengutronix'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Ansgar Lindwedel', 
    topic = 'To be defined', 
    affiliation = 'SDV Eclipse', 
    time = '13:30', 
    room = 'To be defined', 
    link = 'presentation_sdv_eclipse'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Andrew Katz', 
    topic = 'To be defined', 
    affiliation = 'Openchain', 
    time = '14:00', 
    room = 'To be defined', 
    link = 'presentation_openchain'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Marcel Kurzmann', 
    topic = 'To be defined', 
    affiliation = 'ORT', 
    time = '15:00', 
    room = 'To be defined', 
    link = 'presentation_ort'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'C. Emde', 
    topic = 'To be defined', 
    affiliation = 'OSADL', 
    time = '15:30', 
    room = 'To be defined', 
    link = 'presentation_osadl'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Michael Methner', 
    topic = 'DLT in a nutshell', 
    affiliation = 'ADIT', 
    time = '16:00', 
    room = 'To be defined', 
    link = 'presentation_adit1'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Stephan-Tobias Alsleben', 
    topic = 'Working with embedded hardware from anywhere in the world (RTA)', 
    affiliation = 'ADIT', 
    time = '16:30', 
    room = 'To be defined', 
    link = 'presentation_adit2'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Holger Smolinski', 
    topic = 'Contribution Process', 
    affiliation = 'Robert Bosch GmbH', 
    time = 'To be defined', 
    room = 'To be defined', 
    link = 'presentation_bosch'
  ) }}

  {{ tiles.presentation_tile(
    presenter = 'Michael Plagge', 
    topic = 'To be definde', 
    affiliation = 'Eclipse Foundation', 
    time = 'To be defined', 
    room = 'To be defined', 
    link = 'presentation_eclipse_foundation'
  ) }}

{% endcall %}