---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
       
      email: F.A.Simoes@bsms.ac.uk
      phone: +44 1273 877041
      address:
        street: Medical Research Building, University of Sussex
        city: Brighton
        region: Falmer
        postcode: 'BN1 9PS'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '50.864007'
        longitude: '-0.084748'
      directions: Enter the foyer and take the stairs to Office 2.04 on Floor 2
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
