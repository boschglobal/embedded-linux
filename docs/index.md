---
template: home.html
hide:
  - navigation
  - toc
---

{% import 'tiles.md' as tiles %}
{% import 'shadows.md' as shadows %}

# Embedded IoT Linux and OSS day

<!-- Color order: purple, blue, green; dark-green, light-green, dark-purple  -->

{% call tiles.link_tile_wall() %}
  {{ tiles.link_tile('Agenda', 'Conference Agenda', 'agenda', 'images/agenda.svg', color='purple') }}
  {{ tiles.link_tile('Speakers', 'Keynote and Talk Speakers', 'speakers', 'images/speakers.svg', color='blue') }}
  {{ tiles.link_tile('Market Place', 'Market Place Exhibitors', 'market_place', 'images/market.svg', color='green') }}
  {{ tiles.link_tile('Venue', 'Conference Venue Information', 'venue', 'images/directions.svg', color='dark-green') }}
  {{ tiles.link_tile('About', 'Information about the Conference', 'about/faq', 'images/faq.svg', color='light-green') }}
  {{ tiles.link_tile('Contact', 'Contacts for support and questions', 'contact', 'images/contact.svg', color='dark-purple') }}
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

{{ shadows.img_shadow(src='images/marketing_poster_smaller.jpg', alt='poster', width='100%', max_width='650px') }}