---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: nbuttrick@wisc.edu
  address:
    street: 1202 W Johnson St
    city: Madison
    region: WI
    postcode: '53706'
    country: United States
    country_code: US
  coordinates:
    latitude: '43.0725283'
    longitude: '-89.4061911'
  appointment_url: 'https://calendly.com/nick-buttrick'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas


  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: '1'
---
