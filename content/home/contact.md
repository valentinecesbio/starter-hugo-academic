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
  email: valentine.bellet@univ-toulouse.fr
  address:
    street: 18 avenue Edouard Belin
    city: TOULOUSE
    postcode: '31400'
    country: France
    country_code: FR
  coordinates:
    latitude: '43.561203'
    longitude: '1.4776222'

design:
  columns: '2'
---
