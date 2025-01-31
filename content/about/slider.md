---
widget: slider
weight: 10
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3500

content:
  slides:
    - title: 👋 Welcome!
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.5
        media: working.jpg
        fit: cover
    - title: Events
      content: 'Attend talks, movie screenings and bond with your peers'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.5
        media: zoom_stock.jpg
        fit: cover
      link:
        icon: chalkboard-teacher
        icon_pack: fas
        text: Peek our upcoming events
        url: ../event/
    - title: PsyConnect Statistics Support Group
      content: 'Meet fellow psychology majors, bounce ideas, questions and seek help from your seniors!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: stats_avatar.jpg
        fit: cover
      link:
        icon: comments
        icon_pack: fas
        text: Join our telegram channel
        url: 'https://t.me/+FHOEbxCRYJw0ODU1'
    - title: Want to find out more or contribute in a greater capacity?
      content: 'Get in touch with us!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: email.jpg
        fit: cover
      link:
        icon: envelope
        icon_pack: fas
        text: Contact Us
        url: ../contact/
---
