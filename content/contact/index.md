---
title: Contact
date: 2022-10-24

type: landing

sections:
   - block: contact
    content:
      title: Contact
      text: |
        email: F.A.Simoes@bsms.ac.uk
        phone: +44 1273 877041
        address:
          street: Medical Research Building, University of Sussex
          city: Falmer
          region: Brighton
          postcode: 'BN1 9PS'
          country: United Kingdom
          country_code: UK
          coordinates:
            latitude: '50.86407'
            longitude: '-0.084748'
          directions: Enter the Medical Research Building (note this is behind the Medical Teaching Building) and call reception. We are on the second floor, up the stairs through the security door.
    css_class: 'custom-contact-block'

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
          captcha: true
    design:
      columns: '1'


---
