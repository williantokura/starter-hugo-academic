---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: willian.tokura@ufac.br
  phone: 
  address: Rodovia BR 364, Km 04
    street:  Distrito Industrial
    city: Rio Branco
    region: AC
    postcode: '94305'
    country: Brazil
    country_code: BR
  # coordinates:
   # latitude: '37.4275'
   # longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
   # - icon: twitter
   #   icon_pack: fab
   #   name: DM Me
   #   link: 'https://twitter.com/Twitter'
   # - icon: video
   #   icon_pack: fas
   #   name: Zoom Me
   #   link: 'https://zoom.com'

design:
  columns: '2'
---
