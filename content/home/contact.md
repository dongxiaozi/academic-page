---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

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
  email: handongxiao@shu.edu.cn
  phone: +86 15316008906
  address:
    street: No.99, Shangda Road
    city: Shanghai
    #region: CA
    postcode: '200444'
    country: China
    #country_code: US
  coordinates:
    latitude: '31.31671'
    longitude: '121.39215'
  directions: 429A, Building 9, East District

design:
  columns: '2'
---
