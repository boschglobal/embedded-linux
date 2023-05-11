---
hide:
  - toc
  - navigation
---

{% import 'tiles.md' as tiles %}

# Contact

{% call tiles.contact_tile_wall() %}

  {{ tiles.contact_tile_image('../images/fofi.png', 
                              'Fotini Gaidatzi-Lueken', 
                              'Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Fotini<br/>Gaidatzi-Lueken', 
                        'Conference<br/>Organization', 
                        '', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}

  {{ tiles.contact_tile_image('../images/philipp.png', 
                              'Philipp Ahmann', 
                              'Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Philipp<br/>Ahmann', 
                        'Business<br/>Development<br/>Manager', 
                        '', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  
  {{ tiles.contact_tile_image('../images/dirk.png', 
                              'Dirk Sanderschäfer', 
                              'Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Dirk<br/>Sanderschäfer', 
                        'Project<br/>Lead', 
                        '', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}
  
   {{ tiles.contact_tile_image('../images/thomas.png', 
                              'Thomas Noserke', 
                              'Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}
  {{ tiles.contact_tile('Thomas<br/>Noserke', 
                        'Technical<br/>Project Lead',
                        '',
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}

  {{ tiles.contact_tile_image('../images/top97_logo_whitespace.svg',
                              'Embedded IOT Linux@Bosch',
                              'Mailbox.EmbeddedLinuxBosch@de.bosch.com') }}

  {{ tiles.contact_tile('Team<br/>Mailbox', 
                        '', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        'Mailbox.EmbeddedLinuxBosch@de.bosch.com', 
                        color='green-slight-fade') }}

{% endcall %}
