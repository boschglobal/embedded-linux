---
hide:
  - toc
  - navigation
---

{% import 'tiles.md' as tiles %}

# Contact

{% call tiles.contact_tile_wall() %}
  {{ tiles.contact_tile('Fotini<br/>Gaidatzi-Lueken', 
                        'Conference<br/>Organization', 
                        '', 
                        'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/fofi.png', 
                              'Fotini Gaidatzi-Lueken', 
                              'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Team<br/>Mailbox', 
                        '', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/philipp.png', 
                              'Philipp Ahmann', 
                              'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Philipp<br/>Ahmann', 
                        'Business<br/>Development<br/>Manager', 
                        '', 
                        'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  
  {{ tiles.contact_tile_image('../images/dirk.png', 
                              'Dirk Sanderschäfer', 
                              'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Dirk<br/>Sanderschäfer', 
                        'Project Lead', 
                        '', 
                        'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/top97_logo_whitespace.svg',
                              'Embedded IOT Linux@Bosch',
                              'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Thomas<br/>Noserke', 
                        'Technical<br/>Project Lead',
                        '',
                        'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/thomas.png', 
                              'Thomas Noserke', 
                              'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
{% endcall %}
