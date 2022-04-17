---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Leave me a name, contact info, and a short message I will get back to you!

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
  email: vsamuel1121@gmail.com
  phone: Email Me Please!
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter/notv1c'
    - icon: telegram
      icon_pack: fab
      name: Telegram
      link: 'https://telegram.com/'

design:
  columns: '2'
---
