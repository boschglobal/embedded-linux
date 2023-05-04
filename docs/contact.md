---
hide:
  - toc
  - navigation
---

{% import 'tiles.md' as tiles %}

# Contact

{% call tiles.contact_tile_wall() %}
  {{ tiles.contact_tile('Fotini<br/>Gaidatzi-Lueken', 'Conference<br/>Organization', 'Fotini.Gaidatzi-Lueken@de.bosch.com', color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/fofi.png', 'Fotini Gaidatzi-Lueken', 'mailto:Fotini.Gaidatzi-Lueken@de.bosch.com') }}
  {{ tiles.contact_tile('Team<br/>Mailbox', '', 'Mailbox.EmbeddedLinuxBosch@de.bosch.com', color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/philipp.png', 'Philipp Ahmann', 'mailto:Philipp.Ahmannn@de.bosch.com') }}
  {{ tiles.contact_tile('Philipp<br/>Ahmann', 'Business<br/>Development<br/>Manager', 'Philipp.Ahmann@de.bosch.com', color='green-slight-fade') }}
  
  {{ tiles.contact_tile_image('../images/dirk.png', 'Dirk Sanderschäfer', 'mailto:Dirk.Sanderschaefer@de.bosch.com') }}
  {{ tiles.contact_tile('Dirk<br/>Sanderschäfer', 'Project Lead', 'Dirk.Sanderschaefer@de.bosch.com', color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/top97_logo_whitespace.svg', '', 'mailto:Mailbox.EmbeddedLinuxBosch@de.bosch.com', color='green-slight-fade') }}
  {{ tiles.contact_tile('Thomas<br/>Noserke', 'Technical<br/>Project Lead', 'Thomas.Noserke@de.bosch.com', color='green-slight-fade') }}
  {{ tiles.contact_tile_image('../images/thomas.png', 'Thomas Noserke', 'mailto:Thomas.Noserke@de.bosch.com') }}
{% endcall %}
