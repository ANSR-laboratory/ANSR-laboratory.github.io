---
# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: 'contact.png'

sections:
  - block: contact
    content:
      title: Contact
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

  #- block: markdown
  #  content:
  #    title:
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: contact.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen
---
