---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      title: ""
      subtitle: ""
      image:
        filename: "placeholder.png"
        focal_point: "center"
    design:
      background:
        color: "transparent"
        image:
          filename: "contact.svg"
          size: cover  # Ensures full width
          position: center
          parallax: false
  - block: contact
    content:
      title: Use the form below to contact the ANSR Lab
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. 
      #email: test@example.org
      #phone: 888 888 88 88
      address:
        street: 115 Mill Street
        city: Belmont
        region: MA
        postcode: 02478
        country: United States
        country_code: US
      coordinates:
        latitude: '42.392085'
        longitude: '-71.191691'
      directions: McLean Imaging Center
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      contact_links:
        - icon: github
          icon_pack: fab
          name: Find Us on GitHub
          link: https://github.com/ANSR-laboratory
    
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
---
