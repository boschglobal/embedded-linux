---
template: home.html
hide:
  - navigation
  - toc
---

{% import 'tiles.md' as tiles %}
{% import 'shadows.md' as shadows %}

# Embedded IoT Linux and OSS day

{% call tiles.tile_wall() %}
  {{ tiles.tile('Speakers', 'Speakers', 'speakers', 'images/speakers.svg', color='purple') }}
  {{ tiles.tile('Agenda', 'Agenda', 'agenda', 'images/agenda.svg', color='blue') }}
  {{ tiles.tile('Directions', 'Directions', 'directions', 'images/directions.svg', color='green') }}
  {{ tiles.tile('Partners', 'Partners', 'partners', 'images/partners.svg', color='dark-green') }}
  {{ tiles.tile('Contact', 'Contact', 'contact', 'images/contact.svg', color='light-green') }}
  {{ tiles.tile('FAQ', 'FAQ', 'faq', 'images/faq.svg', color='dark-purple') }}
{% endcall %}

Welcome to the website of the 1<sup>st</sup> BOSCH internal conference on
Embedded IoT Linux and OSS!

The event will take place in Feuerbach, July 13th and is hosted by TOP97.

The conference shall attract all Bosch employees working on IoT products based
on embedded Linux.  
This includes Automotive, Industrial, Building Technologies, Power Tools, Smart
Home and Home Appliances.  
Our team interacts with those organizational entities in Bosch.  
It is planned to use the conference to demonstrate the potential of community
based collaboration.  
 Bosch participants will be invited to book services and solutions in the context
of the "Bosch Linux Incubation Group".  
Contributors will get in contact to developers, product owner, architects as
well as leaders and decision maker.  
We expect 200-500 guests in total. The conference cannot be opened for public.  
In case you want to meet specific peers or business contacts from BOSCH, let us
know.

{{ shadows.img_shadow(src='images/marketing_poster_smaller.jpg', alt='poster', width='50%') }}